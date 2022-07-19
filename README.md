# Ansible-tutorial

1. Create One ansible control plain node and install ansible.
2. Generate SSH key pair.
3. Create Other client nodes and copy previously generated public key in to authorized_keys file.
4. Check ssh is working between control plan node and client nodes.



-Important Ansible Commands-

1. ansible-inventory --list
2. ansible all -m ping
3. ansible -a "free -m" all
4. ansible -m localhost ping
5. ansible-playbook --syntax-check httpd-install.yml
6. ansible-playbook --check httpd-install.yml
7. ansible-playbook httpd-install.yaml
8. ansible-playbook change-password.yml --extra-vars newpassword=1qaz2wsx


