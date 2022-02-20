
# Encrypt Ansible inventory using vault

```

ansible-vault encrypt inventory
ansible-vault decrypt inventory

When we run the playbook with encrypted inventory file we will get an error 

Run the playbook using the below options

ansible-playbook playbook.yml -i inventory --ask-vault-pass

If we store the password in a file then use the below option to run 

ansible-playbook playbook.yml -i inventory -vault-password-file password.txt

```
