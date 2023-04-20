# Requirements
pkg: ansible
To install # apt-get install ansible

# Ansible
ansible-playbook -i inventory main.yml
ansible-playbook -i inventory main.yml --limit=host_name
