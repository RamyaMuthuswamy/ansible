```    
      ansible-doc apt
      ansible web -m apt -a "name=git state=present"
      ansible web -m apt -a "name=tree state=present"
      ansible db -m apt -a "name=tree state=present"
      ansible db -m apt -a "name=tree state=absent"
      systemctl --list 
     systemctl --all
     ansible db -m service -a "name=docker state=started"
     ansible web -m service -a "name=docker state=started"
     ansible ansible -m service -a "name=docker state=started"
     vim hosts 
     ansible ansible -m service -a "name=docker state=started"
     ls
     vim ansible.cfg 
     ansible ansible -m service -a "name=docker state=started"
     ansible ansible -m service -a "name=docker state=started"
     ansible ansible -m service -a "name=apache2 state=started"
     ansible ansible -m service -a "name=apache2 state=started" -vvv
     ansible ansible -m service -a "name=docker state=started"
     systemctl status docker 
     systemctl stop docker 
    systemctl status docker 
     ansible ansible -m service -a "name=docker state=started"
     systemctl status docker 
     systemctl stop docker 
     ansible ansible -m service -a "name=docker state=started"
     systemctl status ufw 
     ansible all -m service -a "name=ufw state=stopped"
```
