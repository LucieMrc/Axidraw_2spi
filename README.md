# 🚧🚧 Axidraw_2spi 🚧🚧
*[english version](https://github.com/LucieMrc/Axidraw_sp33d)*

**Ou comment utiliser plus ou moins en autonomie l'Axidraw avec Inkscape (ou avec Saxi) et un .svg.**

Prérequis : être à l'atelier num, avoir installé [Inkscape](https://inkscape.org) et [l'extension Axidraw](https://wiki.evilmadscientist.com/Axidraw_Software_Installation).

!['illu''](./images/imageAxidraw.jpg)

## Mise en place

Brancher l'Axidraw et la connecter en USB à l'ordinateur

Ouvrir son .svg avec Inkscape.

Désactiver les moteurs de l'Axidraw avec `Extensions` > `AxiDraw Utilities` > `Disable XY Motors`.

![screen d'Inkscape](./images/screen3.png)

Une fois que les moteurs sont désactivés, déplacer délicatement le porte-crayon vers le coin en haut à droite, sans forcer.

//photo

Placer la feuille en papier sur la plaque en métal, et la fixer avc les aimants.

//photo

Dans l'onglet `Manual`, soulever le porte-crayon avec l'option `Raise the pen`.

Placer le crayon de son choix dans le porte-crayon, de manière à ce qu'il arrive un peu près 1mm au dessus du papier.

//photo

## Contrôles

Ouvrir le menu Axidraw avec `Extensions` > `AxiDraw Control...`.

![screen d'Inkscape](./images/screen1.png)

-> Dans le menu de contrôle Axidraw, chaque onglet contrôle différentes actions qui peuvent s'appliquer en cliquant sur `Apply`.

Le premier onglet `Plotter`, permet de lancer le plot quand on clique sur `Apply`.

![screen d'Inkscape](./images/screen2.png)

Dans l'onglet `Setup`, on peux choisir la hauteur du crayon dans la position up ou down.

![screen d'Inkscape](./images/screen6.png)

Dans l'onglet `Options`, on peux choisir différents réglages, comme la vitesse.

![screen d'Inkscape](./images/screen7.png)

Il est important de s'assurer qu'on a choisit le bon modèle d'Axidraw dans la partie `Config`, pour avoir le bon format de plot : ici l'Axidraw A3 pour être sûr qu'on trace en A3

![screen d'Inkscape](./images/screen10.png)

Dans l'onglet `Manual`, on peux choisir une action physique executée par l'Axidraw quand on clique sur `Apply`.

![screen d'Inkscape](./images/screen4.png)

On peux notamment activer ou désactiver les moteurs. 

![screen d'Inkscape](./images/screen5.png)

Dans l'onglet `Layers`, on peux choisir un calque en particulier à être plotter.

![screen d'Inkscape](./images/screen8.png)

Dans l'onglet `Resume`, on peux choisir une action à faire lorsque qu'on met le plot en pause.

## Plotter le plot

Ouvrir le menu de l'Axidraw, et cliquer sur `Apply` dans l'onglet `Plotter` pour plotter sans différencier les calques. L'Axidraw plottera alors tous les calques visibles.

![screen d'Inkscape](./images/screen2.png)

On peux mettre le plot en pause avec le bouton sur le coté en haut de l'Axidraw.

Pour plot un seul calque à la fois, il faut ajouter un chiffre devant le nom du calque. Par exemple : "1-layerblue", "2-layergreen", etc.

Ensuite, ouvrir l'onglet `Layers`, et choisir quel numéro de calque on veux plotter, puis cliquer sur `Apply`.

![screen d'Inkscape](./images/screen9.png)

![screen d'Inkscape](./images/screen8.png)

# Utiliser Saxi
Pour imprimer avec [saxi](https://github.com/nornagon/saxi), il suffit d'ouvrir le navigateur de l'ordinateur, et ouvrir la page "localhost:9080", puis de drag and drop le fichier .svg sur la page.

La taille de l'image s'adapte automatiquement à la taille du papier (impossible de resizer, on peux uniquement modifier la taille des marges et l'image sera centrée entre ces marges).

![screen de Saxi](./images/saxi.png)

*(image : [le github de saxi](https://github.com/nornagon/saxi))*

# Pour aller plus loin

Le [guide de l'extension Axidraw pour Inkscape](https://www.manualslib.com/manual/1235134/Evil-Mad-Scientist-Axidraw.html).

Une [vidéo qui explique comment utiliser l'extension](https://www.youtube.com/watch?v=r5mhw8-nrg0).

