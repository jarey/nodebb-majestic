![m6_icon.png](http://i.imgur.com/aw2NJOC.png) 
[![Build Status](https://travis-ci.org/cnvo/nodebb-majestic.svg)](https://travis-ci.org/cnvo/nodebb-majestic)

Majestic is a [NodeBB](https://github.com/NodeBB/NodeBB) theme based on HTML5 Broilerplate, gulp, Bowser, and Bootstrap that will help you make better themes. It's a beautiful, responsive theme developed to be an awesome experience no matter what device it's viewed on. We picked color schemes and an appropriate font family comfortable to the eye with a mobile first approach down to the last pixel.


### Features 
* [gulp](http://gulpjs.com/) build script that compiles both sass and less, checks for errors, optimizes images, and concatenates and minifies files.
* [browsersync](http://www.browsersync.io/) for keeping multiple browsers and devices synchronized while testing, along with injecting updated CSS and JS into your browser while you're developing.
* [bowser](http://bower.io/) for front-end package management.
* ...

### Requirements
Majestic requires the following software to be installed:

`nodebb >= 0.8.x`

### Installation

NodeBB expects any installed themes to be installed via `npm`. 
You can install Majestic through the command line by using the following command:

![m6_npm.png](http://i.imgur.com/NWkGZNO.png) 

## Configuration
(WIP)

## Developing
Majestic also uses [gulp](http://gulpjs.com/) as its build system and [Bower](http://bower.io/) to manage front-end packages.

Building the theme requires [node.js](http://nodejs.org/download/). It is recommended that you update to the latest version of npm: `npm install -g npm@latest`.

via the command line:

1. Install [gulp](http://gulpjs.com) and [Bower](http://bower.io/) globally with `npm install -g gulp bower`
2. Navigate to the theme directory, then run `npm install`
3. Run `bower install`

You now have all the necessary dependencies to run the build process.


### Contributing

Interested in contributing to Majestic? Contributions are welcome, and are accepted via pull requests. Please [review these guidelines](https://github.com/cnvo/nodebb-majestic/blob/master/CONTRIBUTING.md) before submitting any pull requests.

### License
Code licensed under [MIT](https://github.com/cnvo/nodebb-majestic/blob/master/LICENSE), documentation under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/).
