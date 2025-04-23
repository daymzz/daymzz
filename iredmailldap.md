DOMAINE AD

![img](https://i.imgur.com/dKzYAiB.png)

DOMAINE MAIL

![img](https://i.imgur.com/hoQdfBN.png)

COMPOSANTS 

![IMG](https://i.imgur.com/RBEIB9A.png)

FIREWALL RULES

![img](https://i.imgur.com/MmxT6iI.png)

VERIF QUERY LDAP


``` ldapsearch -x -H ldap://ad.domaine.local -D 'vmail' -W -b 'OU=Utilisateurs,dc=domaine,dc=local' ```

TEST CONNECTION POSTFIX AVEC COMPTE AD ET GROUPE + COMPTE LIAISON


