# Gathering Facts 

Use setup module to gather facts on the target systems 

```
ansible web -m setup

ansible web -m setup -a "filter=ansible_os_family"
ansible web -m setup -a "filter=ansible_processor"
ansible web -m setup -a "filter=ansible_nodename"
ansible web -m setup  --tree ./setup

``` 
