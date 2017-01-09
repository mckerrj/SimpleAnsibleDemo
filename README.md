## This is a very simple Ansible Demo based on some of the examples in Jeff Geerling's book, Ansible for Devops.  It's a fantastic book.  Get it.
  - Vagrant file for setting up 3 systems: [VagrantFile](https://github.com/mckerrj/SimpleAnsibleDemo/blob/master/Vagrantfile)
  - Hosts file for mapping hosts to actions: [Hosts](https://github.com/mckerrj/SimpleAnsibleDemo/blob/master/ansible/hosts)
  - A Playbook for installing NTP on all three servers: [ntp-playbook.yml](https://github.com/mckerrj/SimpleAnsibleDemo/blob/master/ansible/ntp-playbook.yml)
  - A Playbook for installing django on just the "app" servers: [app-playbook.yml](https://github.com/mckerrj/SimpleAnsibleDemo/blob/master/ansible/app-playbook.yml)
  - A Playbook for installing mariadb on just the DB server and configuring iptables using the IPTables module.  A good example of how to use
  a module instead of a command.  The original command is right in the playbook. [mariadb-playbook.yml](https://github.com/mckerrj/SimpleAnsibleDemo/blob/master/ansible/mariadb-playbook.yml)
