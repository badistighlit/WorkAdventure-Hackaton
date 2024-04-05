# WorkAdventure X Among Us
## Introduction
Pour ce hackathon, notre équipe a développé une version de Among Us dans l'univers de WorkAdventure. Les joueurs peuvent se rassembler dans le hall, former des équipes et commencer à jouer. À l'intérieur du jeu, les joueurs se voient attribuer des rôles en tant que membres d'équipage ou imposteurs, ce qui crée une dynamique de jeu passionnante.

De plus, notre version comprend divers mini-jeux implémentés sur la carte spaceship.tmj, ainsi que de nombreux pièges et passages secrets pour enrichir l'expérience de jeu.

## Comment jouer
### Accès au hall:
Les joueurs peuvent accéder au hall en visitant [/lobby.tmj]. Ici, ils peuvent former des équipes et se préparer à jouer.

### Formation des équipes:
Une fois dans le hall, les joueurs peuvent former des équipes en invitant d'autres joueurs à les rejoindre. Les équipes devraient idéalement avoir un nombre équilibré de membres d'équipage et d'imposteurs.
![image](https://github.com/badistighlit/WorkAdventure-Hackaton/assets/121290363/d3cb5baf-facd-44bc-8ee2-d27982deab30)

### Démarrage d'une partie:
Une fois que l'équipe est prête, le leader de l'équipe peut lancer une partie, et les joueurs se verront attribuer des rôles au hasard.
![image](https://github.com/badistighlit/WorkAdventure-Hackaton/assets/121290363/2c0bf7b8-fba6-42ef-82c8-29a7262ecb86)

### Jouabilité: 
Les membres de l'équipage doivent travailler ensemble pour accomplir des tâches et identifier les imposteurs, tandis que les imposteurs cherchent à éliminer les membres de l'équipage sans être détectés. Le jeu se termine lorsque toutes les tâches sont accomplies (les membres de l'équipage gagnent) ou lorsque les imposteurs éliminent avec succès suffisamment de membres de l'équipage (les imposteurs gagnent).

### Mini-jeux et secrets:
Explorez la carte spaceship.tmj pour découvrir divers mini-jeux, pièges et passages secrets, ajoutant ainsi une couche supplémentaire d'excitation au jeu.
![spaceship](https://github.com/badistighlit/WorkAdventure-Hackaton/assets/121290363/4a78163f-e30a-434f-88e0-1671ab2da73c)



# WorkAdventure Map Starter Kit

![map](./map.png)

This is a starter kit to help you build your own map for [WorkAdventure](https://workadventu.re).

To understand how to use this starter kit, follow the tutorial at [https://workadventu.re/map-building](https://workadventu.re/map-building).

## Structure
* *public*: Static files like PDFs or audio files
* *src*: Scripts files
* *tilesets*: All tilesets
* *map.tmj*: Map file
* *map.png*: The map thumbnail displayed on the in-game map information

If you want to use more than one map file, just add the new map file on root or in a folder.

we recommend using 500x500 images for the map thumbnails.

If you are going to create custom websites to embed in the map, please reference the HTML files in the `input` option in *vite.config.js*.

## Requirements

Node.js version >=17

## Installation

With npm installed (comes with [node](https://nodejs.org/en/)), run the following commands into a terminal in the root directory of this project:

```shell
npm install
npm run dev
```

## Test production map

You can test the optimized map as it will be in production:
```sh
npm run build
npm run prod
```

## Licenses

This project contains multiple licenses as follows:

* [Code license](./LICENSE.code) *(all files except those for other licenses)*
* [Map license](./LICENSE.map) *(`map.tmj` and the map visual as well)*
* [Assets license](./LICENSE.assets) *(the files inside the `src/assets/` folder)*

### About third party assets

If you add third party assets in your map, do not forget to:
1. Credit the author and license with the "tilesetCopyright" property present in the properties of each tilesets in the `map.tmj` file
2. Add the license text in LICENSE.assets
