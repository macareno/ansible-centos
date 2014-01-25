ansible-centos
==============

I'm learning to use Ansible and I want to automate the deployment of several applications on centos with Plesk Panel.

Command to execute ansible with vagrant:

ansible-playbook -i vagrant_ansible_inventory_default --private-key=~/.vagrant.d/insecure_private_key -u vagrant --sudo ../centos-ansible/provisioner/index.yml