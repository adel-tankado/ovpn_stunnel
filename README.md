
This is a set of roles for setting up your own VPN based on OpenVPN.  
It includes the possibility of integration with Stunnel, Unbound DNS, and Pi-Hole.  
Ansible is run in a virtual environment using the following commands:
```bash
$ source ansible_venv/bin/activate
$ ansible-playbook -i inventory.ini playbooks/vpn_pack.yml
```
If you need to install dependencies, you can use 
```bash
pip3 install -r requirements.txt
```
but ansible_venv already contains the necessary libraries.
