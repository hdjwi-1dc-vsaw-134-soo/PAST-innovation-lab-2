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

<<<<<<< HEAD
There are five virtual campuses in this repository.
=======
If you are going to create custom websites to embed in the map, please reference the HTML files in the `input` option in *vite.config.js*.
>>>>>>> parent of b0e273b (readme)

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

<<<<<<< HEAD
![map](eco-school-readme.png)

Map name: Eco School.

## Copyright
=======
This project contains multiple licenses as follows:
>>>>>>> parent of b0e273b (readme)

* [Code license](./LICENSE.code) *(all files except those for other licenses)*
* [Map license](./LICENSE.map) *(`map.tmj` and the map visual as well)*
* [Assets license](./LICENSE.assets) *(the files inside the `src/assets/` folder)*

### About third party assets

If you add third party assets in your map, do not forget to:
1. Credit the author and license with the "tilesetCopyright" property present in the properties of each tilesets in the `map.tmj` file
2. Add the license text in LICENSE.assets
