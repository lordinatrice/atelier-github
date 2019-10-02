# Atelier-github pour [@LesHackeuses](https://leshackeuses.fr/)  [![alt text][1.2]][1]

[1.2]: http://i.imgur.com/wWzX9uB.png (twitter icon without padding)
[1]: https://twitter.com/leshackeuses?lang=fr

Cet atelier présente les outils de collaboration et de versioning Git et Github.

Ouvert à toutes personnes souhaitant en savoir plus sur Github et ses utilisations.

Il n'est pas nécessaire de savoir coder pour participer à cet atelier.

Vous aurez besoin de votre ordinateur, d'une connexion à internet et d'un compte [Github](http://github.com).
## Le versionning et les outils de collaboration
### Qu'est-ce que versioning?
![](/images/naming_convention_versioning.png)

La gestion de versions, permet simplement de pouvoir créer plusieurs versions d'un projet. Ces versions sont alors accessibles et modifiables.
Le "versioning" permet un travail d'équipe simultané, c'est un outil primordial pour le **travail collaboratif**.

Il permet 
- d'établir un **historique** des modifications 
- de **récupérer des versions anterieures** du projet en cas de problème.

### Qu'est-ce que Github?
![](/images/github_octocat_logo.png)

Github est une plateforme web permettant d'héberger et de gérer des projets.

### Qu'est-ce que Git?
![](/images/git_logo2.png)

Un gestionnaire de version qui permet d'enregister l'évolution d'un fichier ou d'un ensemble de fichiers.
Il permet de conserver toutes les versions d'un projet.

Les versions contiendrons ces informations:
- **Quand** le fichier à été modifié
- **Quoi**: le détail de ce qui a été modifié
- **Pourquoi** le fichier a été modifié
- **Qui** a fait ce changement

## Github
### Créer son premier [dépot](https://help.github.com/en/articles/create-a-repo)
1. Cliquer en haut à droite dans le menu **+** et sélectionner "**New repository**"
2. Nommer son repository
3. Ajouter une description (optionnel)
4. Choisir de rendre le repository "Public" ou "Privé"
5. Initialiser le repo avec un **README**
6. Cliquer sur créer 

## Git
### Installation
https://www.linode.com/docs/development/version-control/how-to-install-git-on-linux-mac-and-windows/ 

### Cloner un repository
```
# cloner un repository existant
git clone git@github.com:camilleregnault/atelier-github.git
```
### Ligne de commande Git
###### Commandes
```
# visualiser les commandes git
git config
```
###### Commit
```
# d'abord verifier le status actuel
git status

# Ensuite, ajouter les fichier dans la "zone de transit"
git add <file_1_which_has_been_modified>
git add <file_2_which_has_been_modified>

# verifier le status
git status

# commenter/ decrire le changement
git commit --message "A meaningful message about this change"
```
###### Log
```
# visualiser l'historique des commits
git log

# press q to exit git log
```
###### Push
```
# Envoyer le commit sur github
git push origin <branch_name>

# envoyer sur la branche principale
git push origin master
```


### Les branches
Ce sont des outils permettant le travail collaboratif.
![](/images/gitbranch.png)

```
# Créer un branche
git checkout -b <new_branch_name>

# Aller sur une branche
git checkout <branch_name>

# Aller sur master
git checkout master
```

###### Pull
```
# Récuperer et intégrer un branche ou un autre repo
git pull origin master
```
###### Merge
```
# Fusionner les branches dans master
git merge
```

## Reférences et liens utiles
commandes principales console + git: https://github.com/women-on-rails/week-1
Commencer avec Git: https://www.christopheducamp.com/2013/12/15/github-pour-nuls-partie-1/
https://openclassrooms.com/fr/courses/2342361-gerez-votre-code-avec-git-et-github
https://blog.lesieur.name/comprendre-et-utiliser-git-avec-vos-projets/

Hello World Github: https://guides.github.com/activities/hello-world/#intro
Github flow: https://guides.github.com/introduction/flow/

https://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/

https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners

Installer Git:
https://www.linode.com/docs/development/version-control/how-to-install-git-on-linux-mac-and-windows/
https://git-scm.com/downloads

Versioning: https://git-scm.com/book/fr/v1/D%C3%A9marrage-rapide-%C3%80-propos-de-la-gestion-de-version

http://www.skilly.com/mag/le-versionning-au-service-de-developpeurs/
Readme syntax:
https://help.github.com/en/articles/basic-writing-and-formatting-syntax

Git github guide:https://rogerdudler.github.io/git-guide/index.fr.html

Formater readme: https://help.github.com/en/articles/basic-writing-and-formatting-syntax

Lignes de commande git: https://gist.github.com/aquelito/8596717#file-git_base-md
<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->
