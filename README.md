# Ansible
Ansible is simple open source IT engine which automates application deployment, intra service orchestration, cloud provisioning and many other IT tools.
Ansible is easy to deploy because it does not use any agents or custom security infrastructure.
Ansible uses playbook to describe automation jobs, and playbook uses very simple language i.e. YAML. which is very easy for humans to understand, read and write. Ansible is completely agentless which means Ansible works by connecting your nodes through ssh(by default). But if you want other method for connection like Kerberos, Ansible gives that option to you.

# Ansible Works
Ansible works by connecting to your nodes and pushing out small programs, called "Ansible modules" to them.Ansible then executes these modules (over SSH by default), and removes them when finished. Your library of modules can reside on any machine, and there are no servers, daemons, or databases required. The inventory file provides the list of hosts where the Ansible modules needs to be run and the management node does a SSH connection and executes the small modules on the hosts machine and installs the product/software.

![image](https://github.com/user-attachments/assets/b2e633d0-4492-4a6b-8192-3cf3fda5381e)

# Installation through Apt on Ubuntu Machine
$ sudo apt-get update 

$ sudo apt-get install software-properties-common 

$ sudo apt-add-repository ppa:ansible/ansible 

$ sudo apt-get update 

# Ansible YAML
Ansible uses YAML syntax for expressing Ansible playbooks.  Ansible uses YAML because it is very easy for humans to understand, read and write when compared to other data formats like XML and JSON.

# Ansible ad-hoc commands
Ad-hoc commands are one-liners for executing tasks on remote hosts without writing a playbook.
Syntax:
ansible [pattern] -m [module] -a "[arguments]" [options]
ansible webservers -m shell -a "free -h" --become

$ sudo apt-get install ansible

