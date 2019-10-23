# Task 1

## Tâches associées au sprint 1

| ID | Descriptif | Développeur | État |
| :-: | -- | :-: | :-: |
| #1 | Créer la base de donnée : créer la table Users contenant les champs ID (unsigned int 5), login (varchar 20), mail (varchar 50), password (varchar 30) || TODO |
|#2|Créer la page web d'accueil du site /accueil contenant un bouton "S'inscrire" et un bouton "Se connecter"||TODO|
|#3|Créer la page d'inscription /signup contenant un formulaire avec les champs login, mail, password et un bouton "s'inscrire" et "annuler"|| TODO |
|#4|Créer le fichier de gestion d'inscription (insertion en base de donnée)||TODO|
|#5|Créer la page de connexion /signin contenant un formulaire avec les champs login et password, un bouton "se connecter" et un bouton "annuler"|| TODO |
| #6 |Créer le fichier de gestion de connexion/deconnexion (gestion de la session)||TODO|
|#7|Créer la table Projects avec les champs ID (unsigned int 5), un nom (varchar 40), une description (varchar 250) qui peut etre null||TODO|
|#8|Créer la page "login"/projects contenant la liste de tous les projets appartenant à "login", et un bouton "Ajouter nouveau projet"||TODO|
|#9|Créer la page /newProject contenant un formulaire avec un nom et une description avec un bouton "créer" et un bouton "annuler" pour créer un nouveau projet||TODO|
|#10|Créer le fichier de gestion de création de projet (insertion base de donnée)||TODO|
|#11|Créer la page d'un projet "login"/projects/"nomProjet" contenant les informations sur le projet, avec un bouton "Ajouter un collaborateur"||TODO|
|#12|Créer la page d'ajout d'un collaborateur "login"/projects/"nomProjet"/addMember avec un formulaire contenant un champs pour le login ou le mail et un bouton "ajouter" ou "annuler"||TODO|
|#13|Créer le fichier de gestion d'ajout d'un membre au projet (base de donnée)||TODO|
|#14|Créer la table Issues contenant les champs ID (unsigned int 5), descriptif (varchar 250), difficulté (int 3), priorité (varchar 10) , un état (varchar 10) et un IdProject (clé étrangère vers le projet associé)||TODO|
|#15|Créer la page d'ajout d'issue "login"/projects/"nomProjet"/addIssue contenant un formulaire avec un champs description, difficulté, priorité et état, un bouton "ajouter" et un bouton "annuler"||TODO|
|#16|Créer le fichier de gestion d'ajout d'issue (insertion base de donnée)||TODO|
|#17|Créer la page d'affichage de toutes les issues "login"/projects/"nomProjet"/backlog contenant la liste de toutes les issues liées à "nomProjet" avec un bouton "ajouter", "modifier" et "supprimer"||TODO|
|#18|Créer la gestion de classement d'issues par ordre de difficulté, de priorité ou d'état||TODO|
|#19|Créer la gestion de la suppression (delete base de donnée)||TODO|
|#20|Créer la page de modification d'une issue "login"/projects/"nomProjet"/backlog/"idIssue" contenant un formulaire avec une description, une difficulté, une priorité et un état, un bouton "modifier" et "annuler"||TODO|
|#21|Créer la gestion de la modification (update base de donnée)||TODO|