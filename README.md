### COMMENT AJOUTER DES FICHIERS AU DÉPÔT GIT

1. *Avant* de commencer à travailler sur le fichier, il faut récupérer le travail que l'autre a fait. On travaille dans le terminal, il faut se déplacer dans le dossier où est contenu le dépôt git grâce à la commande ```cd```. Ensuite, il faut taper:
        
 ```git fetch```
	
 Puis:
	
 ```git pull```
	
 Pour récupérer les fichiers sur le serveur.

2. Une fois le travail sur le(s) fichier(s) terminé, il faut ajouter ce fichier dans la 'staging area', d'où il sera envoyé par la suite sur le serveur GitHub, et 'commit' les changements (on peut faire tout ça en une seule commande):	

 ```git commit -a -m "<commentaire_à_insérer_ici>"```

3. Il faut ensuite récupérer ce qu'il y a sur le dépôt, au cas où une autre personne a modifié des fichiers entre temps. On utilise d'abord:
 
  ```git fetch```

 Puis:

 ```git pull origin master```
 	
4. Ensuite, il faut envoyer le tout au dépôt:
	
	```git push```
