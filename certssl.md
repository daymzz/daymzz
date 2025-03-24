# Certificat SSL

## Prérecquis : 
- Avoir un nom de domaine (gratuit sur [duckdns](duckdns.org) )
- Serveur web, ici apache



## Générer un certif

On installe certbot qui permettra la génération du certificat

```apt install certbot python3-certbot-apache -y```

```certbot --apache -d monsite.duckdns.org```
