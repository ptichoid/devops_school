# DevOps practice task repo

This is training repo for different DevOps practices.

### Requirements for the working environment and labs of the Ansible course:
- 3 virtual machines:
    * min 1 vCPU
    * min 512 Mb RAM
    * min 10 Gb system drive
    * OS Centos 7.8 (minimal installation)
  
If you're using Vagrant, you can rollout whole infrastructure from the Vagrantfile taken from this repo.
I used ssh keys as a authentication method, so I don't need to enter passphrase every time I'm launching playbook. 

For using passphrase to access target nodes add *--ask-become-pass* ad-hoc key.
Default loginpass for both nodes is *vagrant/vagrant*.

Inventory file located in *devops_school/Ansible/inventory/nodes.ini*