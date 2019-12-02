# Releases

## Release v0.1.0

Date de cette release : 08/11/19 - 16h10

Liens pour le téléchargement : https://github.com/FatimaEzzahraBakir/CDP_G2_Equipe2_Release/releases/tag/CDP

### Liste des User Stories présentes dans cette release

| ID  |  Description    | Difficulté  | Priorité  |    État    |
|---|------|---|---|--------|
| #1 | En tant que visiteur je souhaite pouvoir m'inscrire en introduisant mon login (varchar de 20) , mon adresse mail (vérifier qu'elle est valide, en contenant un "@", varchar 50)  et mon password (varchar 30) et cliquer sur le bouton "S'inscrire" pour s'inscrire, ou le bouton "Annuler" pour retourner à la page d'accueil | 3 | Low | DONE|
| #2 | En tant qu’utilisateur je souhaite pouvoir me connecter en saisissant mon login et password et cliquer sur le bouton "Se connecter". Si les identifiants sont les bons, on redirige vers la page des projets associée à mon compte. Et pouvoir me déconnecter en cliquant sur le bouton "Se déconnecter" | 2 | Low | DONE|
| #3 | En tant qu'utilisateur je souhaite pouvoir créer un projet en lui donnant un nom (varchar 40) et une description (varchar 250), qui peut être optionnelle, et appuyer sur le bouton "Créer" pour l'enregistrer ou sur le bouton "Annuler" pour revenir en arrière| 2 | Low | DONE|
| #4 | En tant qu'utilisateur je souhaite pouvoir inviter des personnes, ayant déjà créé un compte, en leur donnant un rôle (développeur, ...) en cliquant sur le bouton "Ajouter" sur la page d'un projet| 2 | Low | DONE|
| #5 | En tant qu’utilisateur, je souhaite pouvoir ajouter une issue dans un backlog de mon projet qui contient un ID (unsigned int 5), un descriptif (varchar 250), une difficulté (int 3), une priorité (varchar 10) et un état (varchar 10) en cliquant sur le bouton "Ajouter" après avoir rempli le formulaire| 2 | High | DOING|
| #6 | En tant qu’utilisateur, je souhaite pouvoir supprimer une issue de mon projet en cliquant sur le bouton "Supprimer", ou modifier son descriptif, sa difficulté, sa priorité et son état en cliquant sur le bouton "Modifier"| 2 | High | DONE|
| #7 | En tant qu’utilisateur, je souhaite pouvoir afficher la liste de toutes les issues de mon projet afin de pouvoir les classer par ordre de difficulté, de priorité ou d’état | 2 | High | DONE|
| #22 | En tant qu’utilisateur, je souhaite modifier le nom ou la description du projet en cliquant sur le bouton "Modifier" ou supprimer en cliquant sur le bouton "Supprimer" un projet| 2 | Low | DONE|

## Release v0.2.0

Date de cette release : 22/11/19 - 16h01

Liens pour le téléchargement : https://github.com/FatimaEzzahraBakir/CDP_G2_Equipe2_Release/releases/tag/CDP_v0.2.0

### Liste des User Stories présentes dans cette release

| ID  |  Description    | Difficulté  | Priorité  |    État    |    Sprint associé    |
|---|------|---|---|--------|-----|
| #7 | En tant qu’utilisateur, je souhaite pouvoir afficher la liste de toutes les issues de mon projet afin de pouvoir les classer par ordre de difficulté, de priorité ou d’état | 2 | High | DONE | 1 |
| #8| En tant qu'utilisateur je souhaite pouvoir choisir un projet dans la liste des différents projets auxquels je participe pour accéder à son Backlog et ses sprints | 2 | High | DONE| 2|
| #9 | En tant qu’utilisateur je souhaite pouvoir lister les tâches d’un projet et les classer par ordre alphabétique ou par issues associées | 3 | High | DONE | 2 |
| #10 | En tant qu’utilisateur je souhaite pouvoir ajouter des tâches, reliées à des issues, avec un ID (unsigned int 5) une definition of done (varchar 500), un état (varchar 10), une date de début (Date) et une durée (double 3) à un projet en cliquant sur le bouton "Ajouter" après avoir rempli le formulaire| 1 | High | DONE |  2|
| #11 | En tant qu’utilisateur je souhaite pouvoir modifier la définition of done, l'état d'une tâche (“TODO” , “DOING” , “DONE”), sa date de début et sa durée en cliquant sur le bouton "Modifier" et supprimer les tâches d’un projet en cliquant sur le bouton "Supprimer" | 2 | High | DONE |2  |
| #12 | En tant qu’utilisateur je souhaite pouvoir assigner une tâche à une personne en cliquant sur le bouton "Assigner" associé à une tâche |1 | High | DONE | 2 |
| #14 | En tant qu’utilisateur, je peux créer un nouveau Sprint, composée d'un ID (unsigned int 5), un projet associé (Project) et une date de sortie (Date) et une description (varchar 500) en cliquant sur le bouton "Créer un sprint" | 2 | Low | DONE | 2 |
| #15 | En tant qu’utilisateur, je peux modifier la date de sortie, et la description d'un sprint en cliquant sur le bouton "Modifier", supprimer un sprint en cliquant sur le bouton "Supprimer"| 2 | Low | DONE |2  |
| #16 | En tant qu’utilisateur, je peux avoir la liste de mes sprints associés à un projet et les trier par ordre chronologique | 2 | Low | DONE | 2 |
