
This is a set of roles for setting up your own VPN based on OpenVPN.  
It includes the possibility of integration with Stunnel, Unbound DNS, and Pi-Hole.
Ansible is run in a virtual environment using the following commands:
```bash
$ python3 -m venv ansible_venv
$ source ansible_venv/bin/activate
$ pip3 install -r requirements.txt
$ ansible-playbook -i inventory.ini playbooks/vpn_pack.yml
```
