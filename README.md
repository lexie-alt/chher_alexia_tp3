# chher_alexia_tp3

# Thématique de la scène 
Édifice de ville

# États, niveaux et progression 
## Quels sont les niveaux de cette version de ton jeu (au moins 3) ? 
- facile : extérieur building
- moyen : intérieur bureau
- difficile : extérieur toit building

## Comment la difficulté va changer entre ces niveaux ? 
avec plus d'obstacle et/ou plus d'ennemis sur son chemin
- facile : ennemis gardien devant la porte (si le temps) en attendant mettre clé
- moyen : cle 
- difficile : ennmis gardien + cle 

## Quels nouveaux objets ou paramètres seront changés ?
ajout objet et ennemis
- facile : ennemis gardien devant la porte
- moyen : cle 
- difficile : cle couleur

# Programmation d’un système de clé et de porte

## Quelles conditions doivent être complétées pour progresser entre les niveaux ? 
Atteindre le sommet et récupéré l'item choisi.
- atteindre la porte
- récuperer clé ascenceur
- récupérer clé helipcopter

## Où entre différents sections d'un même niveau ?
-clé rouge
-clé bleu 
-clé vert

# Intégration d’une interface graphique HUD («Head-Up Display»)
- indication scene niveau
- clé recoltée affichge
- nombre de vie (au besoin)

## Quels éléments sont importantes à afficher ? À quels moments chaque information doit être affichée (permanentes ou temporaires) ?
- clé temporaire
- mur lock temporaire


## Quelles informations le joueur a besoin pour attendre ses objectifs ?
- recupérer les clés et débloquer le prochain

## Assets
(https://kenney.nl/assets/platformer-art-deluxe) asset
(https://kenney.nl/assets/kenney-fonts) font
(https://kenney.nl/assets/generic-items) items



# Notes de cours
developpement narrratif personage
developpement mecanique personnage
developpement niveaux
developpement sonore

avoir avis de feedback

carte de mapping Mark Brown


layer pour element solide
layer pour element decor
ajout de code for global -> project setting  -> general -> add node = permet garder music tout au long

object obstacle = objet solide qui vont disparaitre = 2d node -> lock + collisonshape = pour faire disparaitre collison -> script 
var id_cle pour specifier cle
add-to-group = grouper ensemble 
Main.cle_collectee.connenect = dans le script main 


area 2d = permet de detecter collision quand un autre node touche un node
collisionshape = donne shape

emit = emettre ce signal

% = username id unique -> how to mark an unique 
$ = relation adresse where is the node

await = attendre que 
veux attendre que son de la cle soit terminer pour destruction sinon cle va disparaitre avant son ou animation

fonction toutes ecrit dans script main 

