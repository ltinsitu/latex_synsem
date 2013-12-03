### COMMENT AJOUTER DES FICHIERS AU DÉPÔT GIT

1. *Avant* de commencer à travailler sur le fichier, il faut récupérer le travail que l'autre a fait. On travaille dans le terminal, il faut se déplacer dans le dossier où est contenu le dépôt git grâce à la commande ```cd```. Ensuite, il faut taper:
        
 ```git fetch```
	
 Puis:
	
 ```git pull```
	
 Pour récupérer les fichiers sur le serveur.

2. Une fois le travail sur le(s) fichier(s) terminé, il faut ajouter ce fichier dans la 'staging area', d'où il sera envoyé par la suite sur le serveur GitHub:	

 ```git add <nom_de_fichier>```

 Ou:

 ```git add .```

 Si on veut que tous les fichiers présents dans le dossier soient ajoutés.
3. On doit ensuite 'commit' les changements:

 ```git commit -m "<commentaire_à_insérer_ici">```

4. Il vaut mieux refaire les deux premières commandes ```git fetch``` et ```git pull``` pour être sûr qu'il n'y a pas de conflit entre les versions (au cas où un autre contributeur a modifié les mêmes parties du fichier en même temps). Si il y a un conflit, il faut se référer à [ce site](https://help.github.com/articles/resolving-a-merge-conflict-from-the-command-line#creating-an-edit-collision) pour mieux comprendre comment faire, et utiliser un outil comme [meld](http://meldmerge.org/) grâce à la commande suivante:
 
 ```git mergetool```
 	
5. Ensuite, il faut envoyer le tout au dépôt:
	
	```git push```
