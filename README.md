# Eat'n Slide

Pour ce projet de retrogaming, nous avons décidé de faire un jeu de type *puzzle*. Nous allons ici vous présenter notre équipe, notre intrigue et notre jeu.
Pour une petite démo, c'est [ici](https://youtu.be/ccE7KZ9qRqQ) (1min).


### Les différents fichiers

Notre projet est disponible sous l'extension *.p8* pour le faire tourner sur la console Pico8, ou sinon en version *HTML* et *JS*. Pour profiter également de l'univers musical de notre jeu, nous vous conseillons de le lancer soit sur Pico8 soit sur le navigateur Mozilla Firefox. 
Nous avons décidé de faire le journal de bord dans ce fichier là.

>Dans le dossier V-english, vous pourrez aussi trouver une version de notre jeu avec l'intrigue en anglais.
	
## L'équipe

Nous sommes une équipe de trois étudiants en deuxième année à Polytech'Nice Sophia. L'équipe est composée de Clément Poueyto, Maëva Lecavelier et Loïc Bertolotto. Clément et Loïc se sont occupés de la partie programmation. Clément a été notre *game designer* donc c'est lui qui a créé les niveaux. Maëva, quant à elle, s'est occupée de la partie graphique, sonore et scénaristique du jeu. 

### Journal de bord

Notre emploi du temps a fait que nous avons principalement travaillé pendant nos vacances, c'est à dire la semaine du 15 avril. Clément avait déjà pris en main le logiciel et commençait à faire le premier niveau pour voir comment le game play allait s'articuler. Il a ensuite developpé la partie des collisions et des évènements (avec les monstres, les téléporteurs, les fleches, les aliments etc...). 

Loïc pour sa part a développé la partie des animations (le changement de position des personnages, les petites étincelles lors du déplacement...). 

Maëva s'est d'abord occupée de créer les personnages (principaux et monstres, avec leurs différents *gestes*) puis les textures du jeu (pierre, glace, arbre...). Ensuite, elle a fait le texte d'intro et de fin qui "se déroule", et la partie de code qui va avec. Enfin, elle a fait les musiques du jeu.

## L'intrigue

> En l'an 18, un froid intense a recouvert la contrée de
> Vallis Bona. Mais celui-ci n'est pas du au hasard : les Scouls,
> une race extraterrestre, ont envahi le pays. Sur leur planète
> gelée ils ne mangent que de la glace. Les humains doivent faire
> face à un dilemne : donner aux Scouls leur meilleur plat ou
> mourir...

Au vu du thème de ce concours (l'anniversaire de Valbonne et Sophia-Antipolis), nous voulions un scénario en rapport avec ces villes. L'année dernière, il y avait eu un épisode de neige qui bloqua les rues. C'est là qu'on a pensé à faire de la glace sur le sol (*oui oui, c'est de la glace*). 

Puis, étant étudiants, près du quartier de Saint-Philippe, nous avons souvent l'habitude d'aller manger là-bas. Et l'un des meilleurs endroits que nous avions trouvé a fermé. Cet épisode nous a fait penser qu'il était difficile de trouver des repas vraiment bons. Voilà pourquoi les objectifs de niveaux sont liés à la nourriture (*parfois il faut un peu d'imagination... Par exemple, pour la tranche de cheddar, ou le pain à hamburger ou encore le donnut rose de Homer Simson...*).

Ensuite, pour les extra-terrestres... Il n'y a pas vraiment d'explication, disons que c'est une facilité scénaristique ! (*on en trouve de partout de nos jours...*)

## Le concept : de l'idée à la confection

L'idée de la neige nous a beaucoup arrangé. En effet, c'était plus simple de programmer un objet qui se déplace en ligne droite jusqu'à un obstacle, que de faire un déplacement "case par case". De plus nous nous sommes inspirés des arènes des différents jeux Pokemon. Donc voilà pourquoi on a fait ce système de gameplay. L'espace disponible pour développer le jeu nous a fait faire le nombre de niveaux que l'on a (soit 14). 
Entre les niveaux, on peut voir une texture voulant imiter une forêt pour rappeler la Valmasque. On voulait initialement faire des sangliers mais c'était difficile d'en dessiner sur 64 pixels !

Les touches sont simples d'utilisation : les fléches directionnelles pour se déplacer et voilà. Nous avons aussi ajouté quelques fonctionnalités pour diversifier le jeu, comme des téléporteurs, des monstres, des flèches qui forcent la direction, etc... 

Pour une petite démonstration du gameplay, c'est [ici](https://youtu.be/ccE7KZ9qRqQ) ! Et si jamais vous êtes bloqués à un niveau, vous trouverez les solutions dans cette [vidéo](https://youtu.be/iMSumCmPJYw) (vidéo supplémentaire de plus de 6 min)
> Pour changer de personnage ou de niveau (si débloqué) il suffit d'appuyer sur les flèches directionnelles ! 

## Nos sources
Pour les graphismes, c'est beaucoup Minecraft qui nous a inspirés, surtout pour la glace et les pierres. Après, Maëva apprécie particulièrement le pixel art et s'est amusée sur cette partie. 

Pour faire les musiques, aucun d'entre nous n'a l'oreille musicale, c'est comme si on partait de rien... Donc on a du s'aider de tutoriels. Maëva a utilisé les vidéos de *Gruber* sur Youtube (plus spécialement *"creating a drum beat"* et la série sur *"the pentonic scale"*). Le petit jingle de victoire à la fin du 14ème niveau est fortement inspiré du son de l'ouverture d'un coffre dans la série de jeu vidéos *Zelda*. 

Au début de notre aventure sur Pico8, nous n'avions aucune base sur cet univers. Donc pour comprendre comment fonctionnent la console, l'aspect graphique, les fonctions principales (_update, _init, _draw), etc... Clément a suivi les tutoriels de *Blog Création de Jeux Vidéo*, sur Youtube également, et plus spécialement les vidéos de la série  *"PICO-8 Month"*. 

## 
Merci d'avoir lu jusqu'au bout cette petite présentation ! Voici quelques screenshot du jeu :) 

![Menu](https://lh3.googleusercontent.com/0vpwel8aYDW5PGlUJk5gNC5QYAOAvuGUo8-9hWv477-zqrPSei2c0FS9lWyxnNnRJr5rvg_uKrlHhw=s300 "Menu")   ![Introduction](https://lh3.googleusercontent.com/yoLbW3wkFpoTFB8Tz70xXsQZl88YUqrm9EHWiB46kYXdScMQBYtjqwEsyRZcKY4KEtRCdPFnkoPiuw=s300 "Introduction")
![Niveau 1](https://lh3.googleusercontent.com/LC4KR2ypnz5t6Pw3v-TQ7SjGidppeNTzFk6H82Mb78dFoYeMczQvmSb-bG0uw5pMqFbpHPITEQunTw=s300 "Niveau 1")  ![Niveau 4](https://lh3.googleusercontent.com/knXBg8zcx4dBYLJ2mGbuPjlkV14c_egkPxJCstEu5kjdnXuBKMir7oxH9uwYQ3H6CaOUoISVMuUF4g=s300 "Niveau 4")
 ![Dernier niveau](https://lh3.googleusercontent.com/8Iresl8czFSh1ZYRJIH7j57RHOvkZaAGtx0_Mhiwny1Z2X3AcYyfmhsUbRjPr3e0rV5ivBYX8ZMqIA=s300 "Niveau 14") ![Fin](https://lh3.googleusercontent.com/uyb9AvEVTYn3r76E8yUvct2A9rdLCt8RQ8ksZosvNWS0pFVHCKpifJeDlei69B4Q6-Aw-lryO37Wrg=s300 "Fin") 

Amusez vous bien ! 
