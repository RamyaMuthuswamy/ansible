# ansible


1.sudo apt-get update


//sudo apt install software-properties-common

sudo apt-add-repository ppa:ansible/ansible

sudo apt update 

sudo apt install anisible


on host

sudo apt-get update 

sudo apt-get install python

Setting up our node

sudo nano /etc/ansible/hosts


[group_name]

ALIAS NODE_IP



Save and close that file. You can now test this by pinging all of your added nodes with the command:

ansible -m ping all
