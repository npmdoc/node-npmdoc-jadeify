# npmdoc-jadeify

#### api documentation for  jadeify (v4.6.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-jadeify.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jadeify) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jadeify.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jadeify)

#### A browserify transform for turning .jade files into template functions

[![NPM](https://nodei.co/npm/jadeify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jadeify)

- [https://npmdoc.github.io/node-npmdoc-jadeify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jadeify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jadeify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jadeify/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jadeify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jadeify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jadeify",
    "description": "A browserify transform for turning .jade files into template functions",
    "keywords": [
        "browserify",
        "jade",
        "templates",
        "templating",
        "transform"
    ],
    "version": "4.6.0",
    "author": "Domenic Denicola <d@domenic.me> (https://domenic.me/)",
    "license": "WTFPL",
    "repository": "domenic/jadeify",
    "main": "lib/jadeify.js",
    "files": [
        "lib/"
    ],
    "scripts": {
        "test": "mocha",
        "lint": "jshint lib"
    },
    "dependencies": {
        "through": "^2.3.6"
    },
    "peerDependencies": {
        "browserify": ">= 2.4.0 < 14",
        "jade": "^1.9.2"
    },
    "devDependencies": {
        "browserify": "^13.0.0",
        "concat-stream": "^1.5.0",
        "jade": "^1.11.0",
        "jsdom": "^7.0.2",
        "jshint": "^2.8.0",
        "mocha": "^2.2.5"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
