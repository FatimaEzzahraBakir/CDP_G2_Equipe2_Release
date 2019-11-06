# Task 1

## Tâches associées au sprint 1

| ID | Descriptif | Développeur | État | Issue associée | Coût |
| :-: | -- | :-: | :-: | :-: | :-: |
| #1 | Créer la base de donnée : créer la table Users contenant les champs ID (unsigned int 5), login (varchar 20), mail (varchar 50), password (varchar 30) | Fatima | DONE | 1 | 1/2 |
|#2|Créer la page web d'accueil du site /accueil contenant un bouton "S'inscrire" et un bouton "Se connecter"| Claire|DONE| 1 | 1/2 |
|#3|Créer la page d'inscription /signup contenant un formulaire avec les champs login, mail, password et un bouton "s'inscrire" et "annuler"| Fatima| DONE | 1 | 1/2 |
|#4|Créer le fichier de gestion d'inscription (insertion en base de donnée)| Cyril |DONE | 1 | 1/2 |
|#5|Créer la page de connexion /signin contenant un formulaire avec les champs login et password, un bouton "se connecter" et un bouton "annuler"| Cyril| DONE | 2 | 1/2 |
| #6 |Créer le fichier de gestion de connexion/deconnexion (gestion de la session)| Cyril |DONE | 2 | 1 |
|#7|Créer la table Projects avec les champs ID (unsigned int 5), un nom (varchar 40), une description (varchar 250) qui peut etre null| Fatima|DONE| 3 | 1/2 |
|#8|Créer la page "login"/projects contenant la liste de tous les projets appartenant à "login", et un bouton "Ajouter nouveau projet"| Cyril |DONE| 3 | 1/2 |
|#9|Créer la page /newProject contenant un formulaire avec un nom et une description avec un bouton "créer" et un bouton "annuler" pour créer un nouveau projet| Claire |DONE| 3 | 1/2 |
|#10|Créer le fichier de gestion de création de projet (insertion base de donnée)| Cyril |DOING| 3 | 1 |
|#11|Créer la page d'un projet "login"/projects/"nomProjet" contenant les informations sur le projet, avec un bouton "Ajouter un collaborateur"| Claire |DOING| 4 | 1/2 |
|#12|Créer la page d'ajout d'un collaborateur "login"/projects/"nomProjet"/addMember avec un formulaire contenant un champs pour le login ou le mail et un bouton "ajouter" ou "annuler"||TODO| 4 | 1/2 |
|#13|Créer le fichier de gestion d'ajout d'un membre au projet (base de donnée)||TODO| 4 | 1 |
|#14|Créer la table Issues contenant les champs ID (unsigned int 5), descriptif (varchar 250), difficulté (int 3), priorité (varchar 10) , un état (varchar 10) et un IdProject (clé étrangère vers le projet associé)| Fatima |DONE| 5 | 1/2 |
|#15|Créer la page d'ajout d'issue "login"/projects/"nomProjet"/addIssue contenant un formulaire avec un champs description, difficulté, priorité et état, un bouton "ajouter" et un bouton "annuler"| Fatima |DOING| 5 | 1/2 |
|#16|Créer le fichier de gestion d'ajout d'issue (insertion base de donnée)| Fatima |DOING| 5 | 1/2 |
|#17|Créer la page d'affichage de toutes les issues "login"/projects/"nomProjet"/backlog contenant la liste de toutes les issues liées à "nomProjet" avec un bouton "ajouter", "modifier" et "supprimer"||TODO| 7 | 1 |
|#18|Créer la gestion de classement d'issues par ordre de difficulté, de priorité ou d'état||TODO| 7 | 1 |
|#19|Créer la gestion de la suppression d'une issue (delete base de donnée)||TODO| 6 | 1/2 |
|#20|Créer la page de modification d'une issue "login"/projects/"nomProjet"/backlog/"idIssue" contenant un formulaire avec une description, une difficulté, une priorité et un état, un bouton "modifier" et "annuler"||TODO| 6 | 1/2 |
|#21|Créer la gestion de la modification d'une issue (update base de donnée)||TODO| 6 | 1 |
