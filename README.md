![redhatansible](https://user-images.githubusercontent.com/31984052/37515320-6f52b720-2930-11e8-9dc6-3fafaf2f46f7.png)

# Learn and automate tasks using ansible 

## Lesson1: Ansible installation in Redhat
 # Prerequisite: 
   Python need to be installed.
   Password less ssh need to be configured between control node and managed nodes.
 
 ## Ansible Architecture:
 ![ansible_arch](https://user-images.githubusercontent.com/31984052/37556346-acedffbe-2a1a-11e8-8370-67311433d992.png) 
 
 ## Ansible components: 
 Control-node: Where ansible is installed.  
 Manage-nodes: All nodes managed by ansible.  
 Modules: Preconfigured python programs available on Control-node pushed and executed on managed nodes.  
 Adhoc commands: simple or individual commands ran from Control-node.  
 Playbooks: Program which is written in yaml/ Json in control-node.   
            It contains single/multiple tasks which will be executed on manage-nodes.  
 
 ## Redhat family:
 #yum install ansible
 
 ## MacOS:
 brew install ansible
 
## Lesson2: Inventory and Ansible adhoc commands 

# Inventory: Place where managed host details are available.  
   Ansible deal with 2 types of inventories.  
   a. Static Inventory.  
   b. Dynamic Inventory.  
# Static Inventory: 
    It can contain list of hostnames,Ipaddress (Ungrouped Hosts).  
    Group of host hostnames,Ipaddress.(Grouped Hosts).  
    Group of grouped hosts (Nested hosts group).  
    
<img width="283" alt="screen shot 2018-03-19 at 9 04 30 am" src="https://user-images.githubusercontent.com/31984052/37576885-a0a9a704-2b54-11e8-8599-e7c01dfe6b1d.png">
    
 # Dynamic Inventory
   Python program which contains hosts details generally provided by cloud providers (GCP,AWS,AZURE).  
   
## Lesson3: Creating simple playbooks
 Documentation in Progress
## Lession4: Ansible variables.
Playbook for creating groups,users, assigning users to respective groups by declaring values in vars_files.
