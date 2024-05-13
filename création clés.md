# créer une clé RSA 4096 sur Ubuntu
```
ssh-keygen -t rsa -b 4096
```

Par défaut, les clés seront stockées dans votre dossier home puis .ssh
Il y aura une clé privée id_rsa à ne pas diffuser et une clé publique id_rsa.pub

Pour visualier la clé
```
cat ~/.ssh/id_rsa.pub
```
