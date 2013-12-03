# COMMENT AJOUTER DES FICHIERS AU DÉPÔT GIT

1. Avant de commencer à travailler sur le fichier, il faut récupérer le travail que l'autre a fait. On travaille dans le terminal, il faut se déplacer dans le dossier où est contenu le dépôt git grâce à la commande ```cd```. Ensuite, il faut taper:

```git fetch```

Puis:

```git pull```

Pour récupérer les fichiers sur le serveur.

2. Pour dire à git que l'on vient de créer un nouveau fichier et que l'on veut l'ajouter au dépôt:

```git add <nom_de_fichier>```

3. Pour 'commit' les changements:

```git commit -m "<commentaire_à_insérer_ici"```

4. Pour envoyer le tout au dépôt:

```git push```
