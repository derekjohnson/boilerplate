# Readme

## v 0.3.0 (2015-04-05)

A modified version of [HTML5 boilerplate](https://github.com/h5bp/html5-boilerplate) with [Sass](http://sass-lang.com/) and [Grunt](http://gruntjs.com/).

### Features

#### HTML
* files built from templates and partials in ./src/ and ./src/parts/

#### CSS
* CSS compiled from Sass in ./src/sass/
* Critical CSS generated per template and added to ./dist/*.html with htmlbuild
* CSS Lint task available

#### JS
* concatenated and minified from ./src/js
* JSHint task available

#### Images

##### SVG images

* SVG's in ./src/assets/svg optimised using svgmin
* Optimised SVG's rasterised using svg2png
* PNG's in ./src/assets/png optimised using imageoptim and imagealpha
* All images flattened and copied to ./dist/images/

##### Icons

* SVG's in /src/assets/icons optimised using svgmin
* grunticon works its magic on them, saving all relevant files to dist/css

#### Server

* Uses connect to serve files in ./dist/ to any device on the same network

#### Grunt

* Tasks loaded using jit-grunt for approximately 1.5s (75%) time saving on `grunt`. Much more on watch tasks.
