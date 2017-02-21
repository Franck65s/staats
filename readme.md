$ mkdir ~/staats

# Crée un répertoire pour votre projet nommé "Hello-World" dans votre répertoire utilisateur local

$ cd ~/staats
# Modifie le répertoire de travail en cours pour votre nouveau répertoire fraîchement créé

$ git init
# Installe les fichiers Git nécessaire
# Initialise le répertoire vite Git dans /Users/you/staats/.git/

$ touch README
# Crée un fichier nommé "README" dans votre répertoire local staats
 git add README
# fait entrer en scène le fichier README, et l'ajoute à la liste des fichiers à committer

$ git commit -m 'premier commit'
# Committe vos fichiers, en ajoutant le message "premier commit"

$ git remote add origin https://github.com/username/staats.git
# Crée un remote nommé "origin" pointant votre dépôt GitHub

$ git push origin master
# Envoie vos commits dans la branche "master" sur GitHub
