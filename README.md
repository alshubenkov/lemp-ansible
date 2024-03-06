# lemp-ansible

Tested Ubuntu 18.04, 20.04

Copy repo 

Create file hosts

[server]
server01 ansible_host=(IP) ansible_port=22 ansible_ssh_pass=password ansible_ssh_user=user ansible_sudo_pass=sudopass ansible_python_interpreter=/usr/bin/python3



Run 

ansible-playbook -i hosts site.yml
