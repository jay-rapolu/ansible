# Ansible 

## What is Ansible ?

***Ansible is a configuration management tool used to provision and configure mutiple servers parallely.***

Ansible uses push based kind of architecture, so it connects to remote servers using ssh do the tasks and the close the connection.

Important things to know or terminologies are

1. Module
2. Adhoc commands
3. Playbook
4. Inventory

### 1. Module 
Module is similar to a command in linux, the module has a name and some arguments and this module will perform the designated tasks for that module.

### 2. Adhoc Commands
Adhoc commands are the inline ansible commands, this is used to perform a task which needs to be done for single time or if the task is emergency and there is no time to create a playbook and push it.

### 3. Playbook
Playbook is a file where we define all our Plays, each play is used to define set of tasks which needs to perform on remote servers. playbook uses yaml syntax.

### 4. Inventory
Inventory is a file where we define all our remote server hostnames or ip addressess and we can classify the servers by grouping the servers which require same configurations.
