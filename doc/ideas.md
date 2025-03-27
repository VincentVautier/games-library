## Ideas

# language
        - English first then french

# Les cartes

[] Cards display order : 
        [] default : alpha
        [] Options : last play date, acquisition date, publishing date, type and/or category, designers, artists, rate, price payed => subclassification alpha for equalitiess. 

[] default elements : image, title, last play/play in progress or 'no play registered', playing time (add official ?)


# Reviews 

## Modèle pour la TODO
Review :
    [] fonctionnalité
    [] sécurité
            [] méthode JOIN 
            [] requêtes préparées
            [] gitignore
    [] Validator
    [] DRY
    [] Prettier

## Elements à vérifier à incrémenter dans ce qui précède une fois que c'est ok 


## Fonctions voulues

[] partage de collection par envoi et sur site (possibilité de collections publiques et privées)

[] consulter les règles d'un jeu

[] Une bannière à la une qui affiche par ordre de priorité et par défilement :
        1. un partie en cours
        2. une campagne en cours
        3. le jeu non joué le plus ancien par acquisition 
        4. les jeux aux parties les plus anciennes ordonnés par notes 

[] un planification des parties ? 

[] afficher les jeux commandés avec infos sur le site, la date, (ou en lien vers le vendeur seulement ?). Ils devront s'effacer lorsqu'ils passeront en owned. 

[] noter le jeu et sa difficulté

## Architecture de l'app

[] Reprendre le Oquiz de la saison 11



## DA et intégration

[] dev en mobil first
[] Logo => quelle IA pour le générer ? 


# Les info voulues pour chaque jeu

 - thumbnail
 - title - link BGG
 - designers - link to owned gmaes of the same designers + link BGG
 - Artist - link to owned gmaes of the same artist + link BGG
 - publisher - link to owned gmaes of the same publisher + link BGG
 - date of publish
 - standalone/expansion => link to family : standalone and expensions owned
 - value
 - price payed : links to owned games of the same rate
 - personnal rating
 - general rating + nbr of voters en petit
 - weight : links to owned games of the same weight
 - weight according to the community + nbr of voters
 - acquisition date
 - date added ? Pas sûr que ce soit utile
 - plays
 - last play
 - status : owned, wishlist, preordered, ordered
 - comment
 - player nbr : : links to owned games of the same nbr of players
 - type : links to owned games of the same type
 - category : links to owned games of the same category
 - mechanism : links to owned games of the same mechanism
 - expansions : owned or not with updating date of information