# Commandes de bases : 

1. git add => Ajouter un fichier à la liste de travail de git
2. git status => Afficher le status de chaque fichiers dans la liste de travail de git
3. git commit => Fait un "snap" de notre projet en instantanné
4. git push => Uploader notre projet sur le github
5. git pull => Récupérer le projet de github sur notre machine en local
6. git init => Initialiser un repot dans le dossier actuel
7. git clone => Récupérer un projet et faire en sorte de le mettre à jour en même temps que notre projet local


# Commandes de config :

1. git config --global user.name "nom"
2. git config --global user.email "mail"

# En plus :

1. Ignorez un fichier/dossier => créer un fichier .gitignore et l'ajouter avec git add

# Gestions des conflits :

**Sur git bash** : il faut d'abord récupérer le fichier sur git hub 'git pull' pour qu'il ajoute ses modifications à notre propre fichier, ensuite nous pouvons renvoyer le fichier avec les différentes modifs 

**Sur Visual Studio** : Lorsque que nous faisons des modifs, Visual Studio voit directement les conflits qui peuvent apparaitre et nous propre de choisir entre accepter les modifs du header 'git hub' ou ceux de Visual Studio ou de mélanger les deux.

# Gestion des branches :

Nous pouvons créer une nouvelle branche sur notre projet en faisant `git branch <NomDeLaBranche>`
Pour aller dedans, il faut utiliser `git checkout <NomDeLaBranche>`
Pour ajouter la branche qu'on vient de créer au master, il faut faire `git push --set-upstream origin <NomDeLaBranche>` quand nous sommes dans la branche en question.
Pour fusionner les branches au master, il faut faire `git merge <NomDeLaBranche>`