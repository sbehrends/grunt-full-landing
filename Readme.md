# Grunt-Website

Initial release for working with HTML, CSS, JS. Has lots of small tools to easely develop.

This tool is a full stack development tool for developing websites. It includes a lot of Grunt tasks working together to make it easy for you to develop. It includes, templates (handlebars), webfont generator (for icons), grunticon (also for SVG or PNG icons but can be used for other tasks like embeding a SVG illustration), sprite generator (image sprite generator with retina compatabilty). And loads of other stuff!!


Yup... when I said full stack, I mean it!

Code
= Templates: You can work with layouts and partials keeping your html organized and modular.
= SASS: It compiles de SASS for you, it watches it and it auto refresh the browser.
= Autoprefixer: Don't ever miss a browser prefix

## Assets

# Vectorial Images
= Grunticon: Packs all your SVG and PNG (mainly icons or illustrations) in a file reducing amount of requests. Also creates PNG fallbacks. Isnt that awesome?
= Webfont: Drop some SVG it will give you a webfont. Useful for icons as well.

# Images
= Spritesmith: Another "image" tool. This will build image sprites (with retina support). The main difference with grunticon is that this is mainly use for more colorfull and complex image that can not be a SVG

# Scripts
= JSCS
= JSHint
= Modernizr custom build

# Other stuff
= Bower ready
= File revision
= Other cool stuff

## Installation

After checkout, execute the following steps

```
npm install
bower install
```

to install third party libraries and development environment.

You may need install fontforge for grunt-webfont. Read more about installation on: https://github.com/sapegin/grunt-webfont

## Start development!



Run

```
grunt serve
```

to boot up a local server

## Builds

To build assets and application for deployment, run

```
grunt build
```

## Versioning

The tool has a samll command for versioning
```
grunt version:project:major/minor/patch/prerelease
```
