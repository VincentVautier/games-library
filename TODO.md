# TODO

## sprint 0 : installation du projet

[x] Associer les récap O,clock aux items du sprint

[x] Création du kanban sur github

[] définir les sprints et alimenter des kanban à partir de là

[] Etudier Myludo et BGG pour dégager les fonctionnalités qui l'on veut retrouver dans notre app

[] définir les rôles (design patterns) => Design Pattern URP (User-Role-Permission). Pas forcément URP car complexe. 

[] établir les grandes lignes de la DA

[] Faire les wireframes qui correspondent au premières fonctions à implémenter :
    [] Page d'acceuil
    [] la collection si différente 
    [] Des pages register et login
    [] wishlist page
    => https://kourou.oclock.io/ressources/fiche-recap/wireframes-mode-demploi/

[] relecture recap bdd : https://kourou.oclock.io/ressources/fiche-recap/bases-de-donnees/ et https://kourou.oclock.io/ressources/recap-quotidien/freyja-e02-organiser-ses-donnees/

[] faire le MCD (drawio ?) => https://kourou.oclock.io/ressources/fiche-recap/mcd-modele-conceptuel-de-donnees/

[] faire le MLD => https://kourou.oclock.io/ressources/fiche-recap/mld/

[] user story => https://kourou.oclock.io/ressources/fiche-recap/user-stories/

[] rédige de fichier sql la bdd à partir des jeux possédés

[] créer la bdd => voir la note et https://kourou.oclock.io/ressources/recap-quotidien/freyja-e03-postgresql-at-home/

[] choix de la méthode : active record/Sequilize ou dataMapper ? => https://kourou.oclock.io/ressources/fiche-recap/this/ et https://kourou.oclock.io/ressources/fiche-recap/les-objets-en-js/ et https://kourou.oclock.io/ressources/fiche-recap/architecture-mvc-model-view-controller/ et https://kourou.oclock.io/ressources/recap-quotidien/freyja-e05-atelier-transverse-poo-et-architecture/

[] choix de l'architecture de l'app : modulaire (un répertoire x dans lequel on trouvera X.ejs, XController.js, XRouter.js, etc.) ou fonctionnelle/traditionnelle (Oquiz) ? Plutôt le dernier. A voir...

[] définir les besoins techniques 

## Sprint 1 : core functions

[] Associer les récap O,clock aux items du sprint

[] init

[] install modules 

[] gitignore : node_module, .env, DS_Store (à vérifier). Reprendre le cours

[] Intégration minimale pour tester le code => https://kourou.oclock.io/ressources/recap-quotidien/freyja-e01-larchitecte-et-le-decorateur/ et https://kourou.oclock.io/ressources/recap-quotidien/freyja-e02-box-model/ et https://kourou.oclock.io/ressources/recap-quotidien/freyja-e03-layout/ et https://kourou.oclock.io/ressources/recap-quotidien/freyja-e04-positions/ et https://kourou.oclock.io/ressources/fiche-recap/evenements/

[] Route '/' et '/collection' si différente

[] Affichage de l'intégralité de la collection

[] route et page ajout d'un jeu

### Review 
    
    [] lecture
    [] sécurité
            [] méthode JOIN (et pas resolve !)
            [] requêtes préparées
            [] vérification du gitignore et du .env
    [] boutons
    [] champs
    [] url        
    [] Validator
    [] clean code :
            [] DRY
            [] commentaires 
            [] méthodes documentées
            [] éviter redondances dans la bdd
            [] optimisation SEO => https://kourou.oclock.io/ressources/fiche-recap/search-engine-optimization/
            [] indentation
            [] Prettier
    [] point-amelioration-feedback.md
    [] Compléter le kanban


## Sprint 2 : filters

[] Associer les récap O,clock aux items du sprint

[] route '/game' et affichage dans un game.ejs

[] intégration d'un filtre dans la collection => voir https://github.com/O-clock-Freyja/s09-ocoffee-correction/blob/jour4/public/js/catalog.js. Cette fonction est appelée dans https://github.com/O-clock-Freyja/s09-ocoffee-correction/blob/jour4/views/pages/catalog.ejs. Voir aussi : https://github.com/O-clock-Freyja/s09-ocoffee-correction/blob/jour4/public/js/header.js. Cette fonction est appelée dans https://github.com/O-clock-Freyja/s09-ocoffee-correction/blob/jour4/views/partials/head.ejs. 

## Sprint 3 : finaliser la DA et l'intégration

[] Associer les récap O,clock aux items du sprint

## Sprint 4 : registration

[] Associer les récap O,clock aux items du sprint (voir dans oquiz controllers/user.js)

[] recap :  https://kourou.oclock.io/ressources/recap-quotidien/freyja-e02-forms/

[] installer l'extension fakefiller ou plutôt populate Form Fields dans la navigateur pour autocompléter les formulaires

[] sécuriser : les champs nom et prénom : installer le module npm sanitize-html et l'importer (voir la doc et voir dans oquiz S11 la fonction store de controllers/user.js)

[]  Sécurier le champ email : voir dans oquiz la fonction validateEmail de validators/emailValidator.js et son exécution dans controllers/user.js. La fonction vient de stackoverflow.com

[] installer express-session et import session from 'express-session' et on le met en app.use dans l'app.js

[] Sécuriser le mdp : 
        [] voir méthode store de oquiz controllers/user.js
        [] hacher le mdp : voir owasp password cheat sheet series + installer et importer node-argon2 de npm => méthode ci-dessus
        [] Pour la culture perso : sha256algorithme.com pour voir comment se passe un hash

[] session utilitsateur => https://kourou.oclock.io/ressources/recap-quotidien/freyja-e01-cookies-et-sessions/


[] Associer les récap O,clock aux items du sprint


## Sprint 5 : wishlist

[] Associer les récap O,clock aux items du sprint


## Sprint ? : finalisation du projet

[] compléter les informations d'installation dans le README.md