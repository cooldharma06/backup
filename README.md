# ansible-devstack
Using this codes you can install deploy openstack in Vagrant machine and also its using ansible for deploying Openstack


Tools used:

1. Vagrant - to  create a Virtual Machine for installing devstack in a virtual environment.
2. Ansible - configuration management tool which will install OpenStack(devstack) in Vagrant vm.


ansible-playbook devstack.yml -u "cool" -v --become --ask-become-pass -vvvv


