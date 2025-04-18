# ansible-role-rendu-hugo

Playbook TEST : 
```
---
- hosts: all
  become: yes
  roles:
    - Wordpress-role
```

ETAPE : 

1) Installer les paquets sur debian
2) Installer les paquets sur rocky
3) Supprimer la page par defauts de apache sur rocky et debian
4) téléchargemment de WordPress
5) on vérifie et configure le fichier php
6) on configure les virtualHost
7) on active les sites
8) on reload les serveur apache 
