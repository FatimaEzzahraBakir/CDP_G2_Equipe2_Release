# CDP_G2_Equipe2_Release

## BackLog

Somme des difficultés = 45

| ID  |  Description    | Difficulté  | Priorité  |    État    |    Sprint associé    |
|---|------|---|---|--------|-----|
| #1 | En tant que visiteur je souhaite pouvoir m'inscrire en introduisant mon login (varchar de 20) , mon adresse mail (vérifier qu'elle est valide, en contenant un "@", varchar 50)  et mon password (varchar 30) et cliquer sur le bouton "S'inscrire" pour s'inscrire, ou le bouton "Annuler" pour retourner à la page d'accueil | 3 | Low | TODO | 1 |
| #2 | En tant qu’utilisateur je souhaite pouvoir me connecter en saisissant mon login et password et cliquer sur le bouton "Se connecter". Si les identifiants sont les bons, on redirige vers la page des projets associée à mon compte. Et pouvoir me déconnecter en cliquant sur le bouton "Se déconnecter" | 2 | Low | TODO | 1 |
| #3 | En tant qu'utilisateur je souhaite pouvoir créer un projet en lui donnant un nom (varchar 40) et une description (varchar 250), qui peut être optionnelle, et appuyer sur le bouton "Créer" pour l'enregistrer ou sur le bouton "Annuler" pour revenir en arrière| 2 | Low | TODO | 1 |
| #4 | En tant qu'utilisateur je souhaite pouvoir inviter des personnes, ayant déjà créé un compte, en leur donnant un rôle (développeur, ...) en cliquant sur le bouton "Ajouter" sur la page d'un projet| 2 | Low | TODO | 1 |
| #5 | En tant qu’utilisateur, je souhaite pouvoir ajouter une issue dans un backlog de mon projet qui contient un ID (unsigned int 5), un descriptif (varchar 250), une difficulté (int 3), une priorité (varchar 10) et un état (varchar 10) en cliquant sur le bouton "Ajouter" après avoir rempli le formulaire| 2 | High | TODO | 1 |
| #6 | En tant qu’utilisateur, je souhaite pouvoir supprimer une issue de mon projet en cliquant sur le bouton "Supprimer", ou modifier son descriptif, sa difficulté, sa priorité et son état en cliquant sur le bouton "Modifier"| 2 | High | TODO | 1 |
| #7 | En tant qu’utilisateur, je souhaite pouvoir afficher la liste de toutes les issues de mon projet afin de pouvoir les classer par ordre de difficulté, de priorité ou d’état | 2 | High | TODO | 1 |
| #8| En tant qu'utilisateur je souhaite pouvoir choisir un projet dans la liste des différents projets auxquels je participe pour accéder à son Backlog et ses sprints | 2 | High | TODO|  |
| #9 | En tant qu’utilisateur je souhaite pouvoir lister les tâches d’un projet et les classer par ordre alphabétique ou par issues associées | 3 | High | TODO |  |
| #10 | En tant qu’utilisateur je souhaite pouvoir ajouter des tâches, reliées à des issues, avec un ID (unsigned int 5) une definition of done (varchar 500), un état (varchar 10), une date de début (Date) et une durée (double 3) à un projet en cliquant sur le bouton "Ajouter" après avoir rempli le formulaire| 1 | High | TODO |  |
| #11 | En tant qu’utilisateur je souhaite pouvoir modifier la définition of done, l'état d'une tâche (“TODO” , “DOING” , “DONE”), sa date de début et sa durée en cliquant sur le bouton "Modifier" et supprimer les tâches d’un projet en cliquant sur le bouton "Supprimer" | 2 | High | TODO |  |
| #12 | En tant qu’utilisateur je souhaite pouvoir assigner une tâche à une personne en cliquant sur le bouton "Assigner" associé à une tâche |1 | High | TODO |  |
| #13 | En tant qu’utilisateur je souhaite pouvoir visualiser les tâches sur un calendrier | 3 | High | TODO |  |
| #14 | En tant qu’utilisateur, je peux créer une nouvelle release, composée d'un ID (unsigned int 5), d'une date de sortie (date), quelles fonctionnalités qu’elle supporte (varchar 250), une documentation utilisateur (varchar 500) pour expliquer comment marche le projet et une documentation administrateur (varchar 500) pour l'installation de cette release en cliquant sur le bouton "Créer une release" | 2 | Low | TODO |  |
| #15 | En tant qu’utilisateur, je peux modifier la date de sortie, les fonctionnalités supportées et la documentation d'une release en cliquant sur le bouton "Modifier", supprimer une release en cliquant sur le bouton "Supprimer" ou archiver une release en cliquant sur le bouton "Archiver" | 2 | Low | TODO |  |
| #16 | En tant qu’utilisateur, je peux avoir la liste de mes releases et les trier par ordre chronologique ou par nom | 2 | Low | TODO |  |
| #17 | En tant qu’utilisateur, je souhaite créer un test avec son ID (unsigned int 5), son nom (varchar 20), son résultat attendu (varchar 20) et son niveau (au choix entre validation et unitaire, varchar 10) en cliquant sur le bouton "Ajouter un test"| 2 | Low | TODO |  |
| #18 | En tant qu’utilisateur, je souhaite supprimer un test en cliquant sur le bouton "Supprimer", ou modifier son résultat attendu en cliquant sur le bouton "Modifier"| 1 | Low | TODO |  |
| #19 | En tant qu’utilisateur, je souhaite pouvoir récuperer le résultat obtenu (varchar 20) à ce test afin de le comparer avec le résultat attendu | 3 | Low | TODO |  |
| #20 | En tant qu’utilisateur, je souhaite créer une documentation utilisateur (varchar 500) en y expliquant les fonctionnalités du projet et une documentation administrateur (varchar 500) pour expliquer comment déployer et faire marcher le projet en cliquant sur le bouton "Ajouter une documentation"| 2 | Low | TODO |  |
| #21 | En tant qu’utilisateur, je souhaite modifier en cliquant sur le bouton "Modifier" ou supprimer en cliquant sur le bouton "Supprimer" une documentation utilisateur ou une documentation administrateur| 2 | Low | TODO |  |
| #22 | En tant qu’utilisateur, je souhaite modifier le nom ou la description du projet en cliquant sur le bouton "Modifier" ou supprimer en cliquant sur le bouton "Supprimer" un projet| 2 | Low | TODO |  |
