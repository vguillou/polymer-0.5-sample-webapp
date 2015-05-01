# A Polymer-based, single-page sample Web App

_(Work in progress !)_

## What

Simple Web App built with Web Components and Polymer (not quite ready yet).

This is intended to be used as a base to start building your own Web App using Polymer, Web COmponents and the Service Worker.
You'll find here :
* a responsive Web App, of course
* an implementation of the Service Worker, allowing to use the Web App offline
* a splash screen (using [splash-element](https://github.com/vguillou/splash-element))
* mobile compatible Web App metadata (including Android, iOS and Windows Phone)
* routing and single-page navigation (using [more-routing](https://github.com/PolymerLabs/more-routing))
* page transition effects
* a page initialisation pattern (using [activable-mixin](https://github.com/vguillou/activable-mixin))
* and more

## How

* Fork on Github/clone this repo
```sh
git clone git://github.com/vguillou/polymer-sample-webapp.git
```

* Install [NodeJS](https://nodejs.org/download/)

* Install [Yeoman](http://yeoman.io/) :
```sh
npm install -g yo
```

* Install [Yeoman generator for Polymer projects](https://github.com/yeoman/generator-polymer#yeoman-generator-for-polymer-projects) :
```sh
npm install -g generator-polymer
```

* Open a terminal at the root of the repo

* Install dependencies : NodeJS' (building tools) and Bower's (Polymer framework, polyfills and web-components) :
```sh
npm install
bower update
```

### Build
```sh
gulp
```
Compiled sources are located in ./dist

### Run
Launch your server of choice or simply
```sh
gulp serve
```
Visit ./app/index.html or ./dist/index.html for the optimized version.

## Demo

Keep in mind this is only a draft ! (transitions, issues with CORS,...)

[Here.](https://vguillou.github.io/sample-app/dist/)

## License

[MIT License](http://opensource.org/licenses/MIT)
