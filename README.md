# Ansible
Ansible is simple open source IT engine which automates application deployment, intra service orchestration, cloud provisioning and many other IT tools.
Ansible is easy to deploy because it does not use any agents or custom security infrastructure.
Ansible uses playbook to describe automation jobs, and playbook uses very simple language i.e. YAML. which is very easy for humans to understand, read and write. Ansible is completely agentless which means Ansible works by connecting your nodes through ssh(by default). But if you want other method for connection like Kerberos, Ansible gives that option to you.

# Ansible Works
Ansible works by connecting to your nodes and pushing out small programs, called "Ansible modules" to them.Ansible then executes these modules (over SSH by default), and removes them when finished. Your library of modules can reside on any machine, and there are no servers, daemons, or databases required.
![image](https://github.com/user-attachments/assets/b2e633d0-4492-4a6b-8192-3cf3fda5381e)
