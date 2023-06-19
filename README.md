# Créer un jeu rétro complet

## Description

[Pico-8](https://www.lexaloffle.com/pico-8.php) est une console imaginaire qui permet de créer, partager, et jouer à des jeux miniatures qui évoquent avec nostalgie les débuts du jeu vidéo grand public.

La console possède un environnement de développement complet, de l'éditeur de code aux graphismes, en passant par la musique. Ses spécifications (écran carré de 128 pixels, 16 couleurs, 4 canaux sonores) vont vous contraindre à la créativité - comme des milliers de créateurs et créatrices avant vous, qui utilisent souvent Pico-8 pour prototyper des jeux, dont certains sont devenus de [grands succès](https://www.youtube.com/watch?v=tkX63L7EW6s).

Nous vous invitons à voir ce projet comme un grand bac à sable où vous allez pouvoir déverser votre imaginaire en équipe afin de proposer une expérience ludique à d'autres joueurs, tout en découvrant un nouveau langage et de nouveaux paradigmes de programmation. Les notions acquises ici sont réutilisables sur des moteurs de jeu avancés, en infographie et dans des projets visuels plus complexes.

## Contraintes

- Durée : 2 semaines
- Moteur : [Pico-8](https://www.lexaloffle.com/pico-8.php)
- Langage : Lua

## Notions abordées

- Moteur de jeu
- Infographie 2D
- Gestion d'équipe

!https://vibe.adatechschool.fr/wp-content/uploads/2020/11/f4b8a92fa631f8e63b6eb2ef453ffafcb62f28c5.gif

## Se préparer

- Télécharger la version du logiciel correspondant à votre système d'exploitation
  - **Version PICO-8 (Beta) v0.2.5c**
    - Mac OS X
    [pico-8_0.2.5c_osx.zip](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ad2528b2-c0d8-4e4e-977e-a36c78424228/pico-8_0.2.5c_osx.zip)
    - Windows
    [pico-8_0.2.5c_windows.zip](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/01a55a11-3fea-42c9-972f-263224e36393/pico-8_0.2.5c_windows.zip)
    - Linux (32-bit)
    [pico-8_0.2.5c_i386.zip](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7615ed2e-ab87-4a3e-8a3e-daed5700b38f/pico-8_0.2.5c_i386.zip)
    - Linux (64-bit)
    [pico-8_0.2.5c_amd64.zip](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6f7404b5-3924-4d30-ae1a-958ba7ff6d46/pico-8_0.2.5c_amd64.zip)
    - Raspberry
    [pico-8_0.2.5c_raspi.zip](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/31c67511-568d-4405-9068-631ad4d934ad/pico-8_0.2.5c_raspi.zip)
  - **Archive - Version PICO-8 (Beta) v0.2.1b**
    - Pico 8 pour macOS
    [pico-8_0.2.1b_osx.zip](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b98344b6-d5c7-4eb2-ad9a-6bb01f166088/pico-8_0.2.1b_osx.zip)
    - Pico 8 pour Windows
    [pico-8_0.2.1b_windows.zip](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/baf5ff11-7503-4101-9492-83bf1f988b37/pico-8_0.2.1b_windows.zip)
    - Pico 8 pour Linux (64 bits)
    [pico-8_0.2.1b_amd64.zip](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5c4d362d-cc48-414d-b3ac-cada12b9e721/pico-8_0.2.1b_amd64.zip)
    - Pico 8 pour Linux (32 bits)
    [pico-8_0.2.1b_i386.zip](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2b291027-95a9-4263-96e5-2230d20a6d45/pico-8_0.2.1b_i386.zip)
- La [documentation](https://www.lexaloffle.com/pico-8.php?page=manual) fournie avec la console est très complète et un point de départ utile.
- Commencez par installer les démos et visitez [splore](https://pico-8.fandom.com/wiki/Splore) sur la console pour découvrir tout son potentiel.
- Comme souvent, nous vous recommandons de commencer avec des tutoriels pour gagner rapidement en confiance.

## Orientation du projet

### Jeux possibles

Nous n'imposons pas de contraintes sur le [game design](https://fr.wikipedia.org/wiki/Game_design), mais vous pouvez partir des styles de jeu les plus populaires en 2D :

- les jeux de plateforme ;
- les RPG "top-down" (jeux de rôles vus du dessus) ;
- les jeux avec défilement vertical (courses de voiture, vaisseaux spatiaux…) ;
- … ou complètement innover, il n'y a pas de limite !

Ces propositions ont quand même en commun de vous faire déplacer des entités (personnages, véhicules) dans un environnement à deux dimensions, avec des événements et des interactions possibles.

Dans l'esprit d'Ada, nous vous invitons à rendre vos jeux accessibles, respectueux de la diversité, et positifs !

A la fin du projet, vous découvrirez comment partager vos jeux : sachez que chacune de vos productions entrera dans l'histoire de l'école et sera jouable par les promotions suivantes. Comment ? On ne vous en dit pas plus pour l'instant ;)

### 1. Je débute

Dans un premier temps, nous vous invitons à :

- Enrichir les fonctions principales du moteur : \_init(), \_update() et \_draw() ;
- Dessiner un _tileset_ puis une carte et l'afficher dans le jeu ;
- Dessiner un _sprite_ et le faire apparaître dans le jeu aux coordonnées voulues ;
- Déplacer votre sprite avec les touches du clavier ;
- Faire en sorte que votre personnage ne sorte pas des bords de la carte et ne puisse pas aller partout, en gérant les collisions grâce aux _flags_ ;
- Faire en sorte que la camera suive votre personnage ;
- Jouer des sons.

### Ressources

- Un [tuto fort sympathique](https://www.youtube.com/watch?v=YXbR0eqPoAw) pour se lancer ;
- Un [site du même auteur](https://fairedesjeux.fr/pico-8/) assez riche qui pourra vous accompagner ;
- Les jeux Pico-8 sont open source… Amusez-vous avec `splore` !

### Objectifs pédagogiques

- Gestion de la boucle de jeu,
- Affichage de sprites,
- Gestion des inputs clavier,
- Collisions 2D.
- Camera 2D,
- Gestion des ressources graphiques et sonores.

### 2. Je suis à l'aise

Dans un second temps, vous pouvez :

- Implémenter des déplacements avancés : sauts, _boosts_, changements de vitesse ;
- Créer des objets qui peuvent être collectés, dont le nombre peut être affiché sur l'interface utilisateur (_HUD_), et qui ajoutent du gameplay (ex. : des clés qui ouvrent des portes) ;
- Animer votre personnage sur plusieurs _frames_ ;
- Animer des éléments de la carte et, pour les _platformers_, ajouter de la parallaxe ;
- Déclencher des événements à certains moments du jeu : changement de musique, déplacements de personnages non-joueurs…
- Créer et afficher joliment des dialogues,
- Ajouter un écran-titre.

Quand vous aurez l'impression d'avoir pris suffisamment de bouteille sur le moteur, profitez-en pour déployer votre créativité et créer un univers entier afin de prolonger la durée de votre jeu ! Niveaux supplémentaires, nouveaux personnages, intrigues…

Ayez vos joueurs à l'esprit et faites-vous et faites-leur plaisir !

### Ressources

- Une [cheat sheet](https://www.lexaloffle.com/bbs/files/16585/PICO-8_Cheat-Sheet_0-9-2.png) avec toutes les commandes et fonctions utiles ;
- Une [super doc un peu avancée](https://mboffin.itch.io/gamedev-with-pico-8-issue1) ;
- Des [tutos de pixel art animé](https://saint11.org/blog/pixel-art-tutorials/), par le game artist de Celeste !

### Objectifs pédagogiques :

- Physique 2D,
- User interface et HUD,
- Animation 2D,
- Gestion des événements,
- Affichage et mise en forme de textes.

### 3. Je veux aller plus loin

Au cours de vos explorations, vous avez pu vous rendre compte que des développeurs et développeuses vont très loin dans leur utilisation de Pico-8 : 3D, multi-joueur en ligne, gestion de la souris…

Il est temps pour vous de pousser les limites de la console ! Voici quelques idées, prévues ou pas dans la doc :

- Intégrer du multijoueur : Pico-8 peut en effet gérer 2 joueurs en local !
- Créer des sonorités immersives avec plusieurs canaux ;
- Utiliser les features non ou peu documentées : gestion de la souris (et du tactile sur mobile), de l'heure, déblocage des 16 couleurs secrètes.

Mais encore, pour les plus déterminées d'entre vous :

- Créer un moteur de jeu 3D simple en rasterization ou en ray casting ;
- Créer un moteur 3D avancé en ray tracing ;
- Il a existé des tentatives de jeux en ligne : où cela en est-il et comment feriez-vous ?
- Enfin, le logiciel fonctionne sur Raspberry Pi… Ça vous donne des idées ? Nous, oui !

### Objectifs pédagogiques

- Gestion avancée des inputs,
- Effets sonores avancés,
- Infographie 3D : rasterization, ray casting, ray tracing,
- Géométrie dans l'espace : matrices,
- Réseau,
- Raspberry Pi.

## Publier votre jeu !

Pico-8 a quelques fonctions magiques d'export des jeux…On vous laisse chercher, mais sachez que vous pouvez en une commande :

- exporter en HTML / JS (partagez ensuite vos créations en un `git push` avec [Github Pages](https://pages.github.com/) ou [Netlify](https://pages.github.com/) !) ;
- exporter en .png (oui oui, une image représentant votre cartouche de jeu et qui en contient l'intégralité) ;
- exporter vos différents assets graphiques et sonores.

Pour partager votre jeu sur splore, il faut passer par le [forum](https://www.lexaloffle.com/bbs/).

Nous aimerions que chaque groupe publie son jeu à la fois sur le web et sur splore. N'hésitez pas à nommer l'école dans la description !

## Ressources générales

### Quelques jeux inspirants à trouver sur splore :

- Dykie Street, un jeu féministe développé par deux françaises,
- Les incroyables jeux en 3D de freds72 (GRally, Freds72_Snow, Ramps),
- PicoTennis2, un jeu de tennis très réussi avec du multijoueur,
- Pico-Ray, un… ray tracer, complet, sans carte graphique RTX,
- Picopolis (un vrai sim city par Jeb, le lead dev de Minecraft),
- Fuz, qui reproduit merveilleusement l'ambiance et les mécaniques du grand classique indé Fez,
- The Story of Zeldo, pour les fans de la saga,
- Two hiking cats have an in depth conversation about life the universe and everything.

### Des chaînes Youtube terriblement cool sur le game design :

- [Game Spectrum](https://www.youtube.com/channel/UCoE1zHB74QsR22l-J6uK53Q)
- [Ludology](https://www.youtube.com/channel/UCLxdRDu1pm9I4F2cjKTJJ0A/videos)
- [Développeuse Du Dimanche](https://www.youtube.com/channel/UCVf2py0nEmhiUH7pryhZdyg)
- [Un bot pourrait faire ça](https://www.youtube.com/channel/UCpfe3Yjy2jGJFRk-D7DVrXw)
- [Atlangames](https://www.youtube.com/channel/UCcpBt3SmtbCJleRvT8yGbkw)
- [Brackeys](https://www.youtube.com/channel/UCYbK_tjZ2OrIZFBvU6CCMiA)
- [Video Game Animation Study](https://www.youtube.com/channel/UC8A3Zig-dNx2kZmy1FovTEA)
- [8-bit Music Theory](https://www.youtube.com/channel/UCeZLO2VgbZHeDcongKzzfOw)

### Sur le web

- [Le site officiel](https://www.lexaloffle.com/pico-8.php)
- [L'API de référence](https://pico-8.fandom.com/wiki/APIReference)
- [Un subreddit discret mais actif](https://www.reddit.com/r/pico8/)
- [Article : PICO-8 et les consoles fantasy](https://medium.com/@bigaston/pico-8-et-les-consoles-fantasy-96a0241aee34)
- [Article : Et si on faisait des jeux vidéos un outil féministe ?](https://www.marieclaire.fr/et-si-on-faisait-des-jeux-videos-un-outil-feministe,1292150.asp)
