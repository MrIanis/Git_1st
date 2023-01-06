# GIT

Git est un système de gestion de versions décentralisé. Il permet de gérer des versions de fichiers et de répertoires. Il permet de travailler en équipe sur un même projet.

## Les commandes de base

### Initialiser un dépôt

Pour initialiser un dépôt, il faut se placer dans le répertoire que l'on souhaite versionner et exécuter la commande suivante :

    git init

### Ajouter un fichier

Pour ajouter un fichier, il faut utiliser la commande suivante :

    git add <fichier>

### Commiter un fichier

Pour commiter un fichier, il faut utiliser la commande suivante :

    git commit -m "<message>"

### Voir l'état du dépôt

Pour voir l'état du dépôt, il faut utiliser la commande suivante :

    git status

### Voir l'historique des commits

Pour voir l'historique des commits, il faut utiliser la commande suivante :

    git log

### Voir les différences entre les commits

Pour voir les différences entre les commits, il faut utiliser la commande suivante :

    git diff

### Ignorer un fichier

Pour ignorer un fichier, il faut créer un fichier `.gitignore` à la racine du projet et y ajouter les fichiers à ignorer.