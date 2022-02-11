# Install Ansible in VM

Get a new ubuntu 20 VM in AWS

Check the python version .It should be > 2.7 or python 3.x

### Install Ansible

```
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible

ansible --version

```

# Create a inventory to run commands in the newly created ec2 instances


Configure the ipaddress of the newly created ec2 instance with the pem file for ssh to work
Ansible will use this to login and execute the commands/scripts

```
ec2-instance ansible_host=18.117.147.182 ansible_user=ubuntu ansible_ssh_private_key_file=/home/ubuntu/gaj/target.pem

```    
Execute the following ansible commands 

```
ansible --version

ansible all -i inventory -m ping

```
