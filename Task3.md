
# Task 3

## Tâches associées au sprint 3

| ID |Description | Definition Of Done| Développeur | État | Issue associée | Coût |
| :-: | -- | -- | :-: | :-: | :-: | :-: |
| #1 | Création des tables pour la base de données | Créer la table Test qui contient les champs ID (unsigned int 5), name (String), expectedResult (String) et obtainedResult (String), level (String). Créer la table Documentation qui contient une description (String), type (String) |  | TODO| 17,20 |  |
| #2 | Créer la page d'un nouveau test | Créer la page /"login"/projects/"idProjet"/tests/newTest qui contient un formulaire avec les champs Nom, Résultat attendu et Niveau, un bouton annuler qui permet de revenir à la page précédente et un bouton ajouter qui ajoute dans la base de données le test avec le contenu des champs. |  | TODO| 17 |  |
| #3 | Afficher la liste de tous les tests d'un projet | Créer la page /"login"/projects/"idProjet"/tests qui affiche tous les tests associés au projet "idProjet" avec les colonnes Nom, Résultat attendu, Résultat obtenu et Niveau, ainsi qu'un bouton "Ajouter un nouveau test" qui ammène vers la page /"login"/projects/"idProjet"/tests/newTest |  | TODO| 17,18,19 |  |
| #1 | Gérer la suppression d'un test | Sur la page /"login"/projects/"idProjet"/tests ajouter un bouton de suppression à côté de chaque tests permettant de supprimer un test en base de donnée. Ce bouton charge /"login"/projects/"idProjet"/tests/delete/"idTest" qui s'occupe du traitement de suppression en supprimant le test de la table Test, et une fois effectué renvoie sur la liste des tests du projet /"login"/projects/"idProjet"/tests |  | TODO| 18|  |
| #1 | Gérer la modification d'un test  | Sur la page /"login"/projects/"idProjet"/tests, ajouter un bouton d'édition à côté de chaque test permettant de se rendre sur /"login"/projects/"idProjet"/test/update/"idTest" contenant un formulaire avec les champs "Nom", "Résultat attendu", "Résultat obtenu" et "Niveau", pré-remplit par les information actuelles du test, un bouton "Annuler" qui permet de revenir à la page précedente, et un bouton "Modifier" qui permet de mettre à jour en base de donnée le test "idTest" avec les nouveaux champs présents dans le formulaire |  | TODO| 18|  |
| #1 | Afficher l'état d'un test | Ajouter un colonne sur la page colonne "Etat" qui affichera un point vert si le résultat attendu d'un test est le même que son résultat obtenu, et sinon un point rouge. |  | TODO| 19 |  |
| #1 | Créer la page d'une nouvelle documentation | Créer la page /"login"/projects/"idProjet"/newDoc contenant un formualaire avec deux choix "documentation utilisateur" ou "documentation administrateur" et un champs où on peut inclure un fichier .txt, un bouton annuler qui revient à la page précédente et un bouton Ajouter qui ajoute dans la base de données le contenu de la documentation sous la forme d'un String, et renvoie sur la page /"login"/projects/"idProjet" quand le traitement est fini|  | TODO| 20 |  |
| #1 | Gérer la modification d'une documentation |  |  | TODO| 21 |  |
| #1 | Gérer la suppression d'une documentation |  |  | TODO| 21 |  |
| #1 | Intégrer Travis | Ajouter travis à notre dépôt Git pour permettre l'intégration continue |  | TODO| - |  |
