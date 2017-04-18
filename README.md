# npmdoc-bunyan

#### api documentation for  [bunyan (v1.8.10)](https://github.com/trentm/node-bunyan#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-bunyan.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-bunyan) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bunyan.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bunyan)

#### a JSON logging library for node.js services

[![NPM](https://nodei.co/npm/bunyan.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bunyan)

- [https://npmdoc.github.io/node-npmdoc-bunyan/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bunyan/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bunyan/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bunyan/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-bunyan/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-bunyan/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "// dtrace-provider": "required for dtrace features",
    "// moment": "required for local time with CLI",
    "// mv": "required for RotatingFileStream",
    "author": {
        "name": "Trent Mick",
        "url": "http://trentm.com"
    },
    "bin": {
        "bunyan": "./bin/bunyan"
    },
    "bugs": {
        "url": "https://github.com/trentm/node-bunyan/issues"
    },
    "contributors": [
        {
            "name": "Trent Mick",
            "url": "http://trentm.com"
        },
        {
            "name": "Mark Cavage",
            "url": "https://github.com/mcavage"
        },
        {
            "name": "Dave Pacheco",
            "url": "https://github.com/davepacheco"
        },
        {
            "name": "Michael Hart",
            "url": "https://github.com/mhart"
        },
        {
            "name": "Isaac Schlueter",
            "url": "https://github.com/isaacs"
        },
        {
            "name": "Rob Gulewich",
            "url": "https://github.com/rgulewich"
        },
        {
            "name": "Bryan Cantrill",
            "url": "https://github.com/bcantrill"
        },
        {
            "name": "Michael Hart",
            "url": "https://github.com/mhart"
        },
        {
            "name": "Simon Wade",
            "url": "https://github.com/aexmachina"
        },
        {
            "name": "https://github.com/glenn-murray-bse"
        },
        {
            "name": "Chakrit Wichian",
            "url": "https://github.com/chakrit"
        },
        {
            "name": "Patrick Mooney",
            "url": "https://github.com/pfmooney"
        },
        {
            "name": "Johan Nordberg",
            "url": "https://github.com/jnordberg"
        },
        {
            "name": "https://github.com/timborodin"
        },
        {
            "name": "Ryan Graham",
            "url": "https://github.com/rmg"
        },
        {
            "name": "Alex Kocharin",
            "url": "https://github.com/rlidwka"
        },
        {
            "name": "Andrei Neculau",
            "url": "https://github.com/andreineculau"
        },
        {
            "name": "Mihai Tomescu",
            "url": "https://github.com/matomesc"
        },
        {
            "name": "Daniel Juhl",
            "url": "https://github.com/danieljuhl"
        },
        {
            "name": "Chris Barber",
            "url": "https://github.com/cb1kenobi"
        },
        {
            "name": "Manuel Schneider",
            "url": "https://github.com/manuelschneider"
        },
        {
            "name": "Martin Gausby",
            "url": "https://github.com/gausby"
        },
        {
            "name": "Stéphan Kochen",
            "url": "https://github.com/stephank"
        },
        {
            "name": "Shakeel Mohamed",
            "url": "https://github.com/shakeelmohamed"
        },
        {
            "name": "Denis Izmaylov",
            "url": "https://github.com/DenisIzmaylov"
        },
        {
            "name": "Guillermo Grau Panea",
            "url": "https://github.com/guigrpa"
        },
        {
            "name": "Mark LeMerise",
            "url": "https://github.com/MarkLeMerise"
        },
        {
            "name": "https://github.com/sometimesalready"
        },
        {
            "name": "Charly Koza",
            "url": "https://github.com/Cactusbone"
        },
        {
            "name": "Thomas Heymann",
            "url": "https://github.com/cyberthom"
        },
        {
            "name": "David M. Lee",
            "url": "https://github.com/leedm777"
        },
        {
            "name": "Marc Udoff",
            "url": "https://github.com/mlucool"
        },
        {
            "name": "Mark Stosberg",
            "url": "https://github.com/markstos"
        },
        {
            "name": "Alexander Ray",
            "url": "https://github.com/aray12"
        },
        {
            "name": "Adam Lynch",
            "url": "https://github.com/adam-lynch"
        },
        {
            "name": "Michael Nisi",
            "url": "https://github.com/michaelnisi"
        },
        {
            "name": "Martijn Schrage",
            "url": "https://github.com/Oblosys"
        },
        {
            "name": "Paul Milham",
            "url": "https://github.com/domrein"
        },
        {
            "name": "Frankie O'Rourke",
            "url": "https://github.com/psfrankie"
        },
        {
            "name": "Cody Mello",
            "url": "https://github.com/melloc"
        },
        {
            "name": "Todd Whiteman",
            "url": "https://github.com/twhiteman"
        },
        {
            "name": "Zach Bjornson",
            "url": "https://github.com/zbjornson"
        }
    ],
    "dependencies": {
        "dtrace-provider": "~0.8",
        "moment": "^2.10.6",
        "mv": "~2",
        "safe-json-stringify": "~1"
    },
    "description": "a JSON logging library for node.js services",
    "devDependencies": {
        "ben": "0.0.0",
        "markdown-toc": "0.12.x",
        "nodeunit": "0.9",
        "vasync": "1.4.3",
        "verror": "1.3.3"
    },
    "directories": {},
    "dist": {
        "shasum": "201fedd26c7080b632f416072f53a90b9a52981c",
        "tarball": "https://registry.npmjs.org/bunyan/-/bunyan-1.8.10.tgz"
    },
    "engines": [
        "node >=0.10.0"
    ],
    "gitHead": "13c86f1d15c192f7b4f73c0cbef18f37606d81ea",
    "homepage": "https://github.com/trentm/node-bunyan#readme",
    "keywords": [
        "log",
        "logging",
        "log4j",
        "json",
        "bunyan"
    ],
    "license": "MIT",
    "main": "./lib/bunyan.js",
    "maintainers": [
        {
            "name": "trentm"
        }
    ],
    "name": "bunyan",
    "optionalDependencies": {
        "dtrace-provider": "~0.8",
        "moment": "^2.10.6",
        "mv": "~2",
        "safe-json-stringify": "~1"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/trentm/node-bunyan.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "1.8.10"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
