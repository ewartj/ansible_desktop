Install ansible:

sudo apt-get install software-properties-common

sudo apt-add-repository ppa:ansible/ansible

sudo apt-get update

sudo apt-get install ansible

To run:

sudo ansible-playbook --connection=local local.yml
