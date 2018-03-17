![redhatansible](https://user-images.githubusercontent.com/31984052/37515320-6f52b720-2930-11e8-9dc6-3fafaf2f46f7.png)

# Learn and automate tasks using ansible 

###Lesson1: Ansible installation in Redhat
 Pre-requiste: 
 Python need to be installed.
 Password less ssh need to be configured between control node and managed nodes.
 
 Ansible components: 
 Control-node: Where ansible is installed.
 Manage-nodes: All nodes managed by ansible.
 Modules: Preconfigured python programs available on Control-node pushed and executed on managed nodes.
 Adhoc commands: simple or individual commands ran from Control-node.
 Playbooks: Program which is written in yaml/ Json in control-node. 
            It contains single/multiple tasks which will be executed on manage-nodes.
 
 Redhat family:
 #yum install ansible
 MacOS:
 brew install ansible
 
###Lesson2: Inventory and Ansible adhoc commands 
 

###Lesson3: Creating simple playbooks

###Lession4: Ansible variables.
Playbook for creating groups,users, assigning users to respective groups by declaring values in vars_files.
