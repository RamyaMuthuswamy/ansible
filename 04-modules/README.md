```    
      ansible-doc apt
      ansible web -m apt -a "name=git state=present"
      ansible web -m apt -a "name=tree state=present"
      ansible web -m apt -a "name=tree state=present"
      ansible web -m apt -a "name=tree state=absent"
     ansible web -m service -a "name=docker state=started"
     ansible web -m service -a "name=apache2 state=started"
     ansible web -m service -a "name=apache2 state=started" -vvv
     systemctl status docker 
     systemctl stop docker 
     ansible web -m service -a "name=docker state=started"
     systemctl status ufw 
     ansible all -m service -a "name=ufw state=stopped"
```
