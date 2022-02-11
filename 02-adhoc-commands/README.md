# Run ad hoc commands in ansible  

```

    ansible-doc -l
    ansible-doc ping

    ansible-doc command
    ansible ec2 -i inventory -m command -a 'df -h'
    ansible ec2 -i inventory -m command -a 'hostname'
    ansible ec2 -i inventory -m command -a 'uname -a'
    ansible ec2 -i inventory -m command -a 'cat /etc/*-release'
    ansible ec2 -i inventory -m command -a 'cat /etc/os-release'
    ansible ec2 -i inventory -m command -a 'cat /etc/*-release'

   ansible ec2 -i inventory -m shell -a 'cat /etc/*-release'
   ansible ec2 -i inventory -m shell -a 'echo "Hello World" > /tmp/test.txt'
   ansible ec2 -i inventory -m shell -a 'cat  /tmp/test.txt'
   ansible ec2 -i inventory -m shell -a 'echo "Hey Training Participants " >> /tmp/test.txt'
   ansible ec2 -i inventory -m shell -a 'cat  /tmp/amit.txt'

```
