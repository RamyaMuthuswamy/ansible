# Provision ec2 instance using ansible

We will create/provision a new ec2 instance using ansible in aws

### Install python and boto and boto3 and awscli and configure awscli

```

sudo pip install boto boto3
sudo pip install awscli
aws configure -> configure the credentials of aws account  

```

### Launch ec2 instance

```

 - name: Launching aws ec2 instance
   hosts: localhost
   gather_facts: false
   tasks:
   - name: Launching ec2 instance with ec2 module
     ec2_instance:
      instance_type: t2.micro
      image: ami-0fb653ca2d3203ac1
      region: us-east-2

```

Run the file with ansible-playbook ec2-launch.yml
