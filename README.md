# npmdoc-styledocco

#### api documentation for  [styledocco (v0.6.6)](http://jacobrask.github.com/styledocco/)  [![npm package](https://img.shields.io/npm/v/npmdoc-styledocco.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-styledocco) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-styledocco.svg)](https://travis-ci.org/npmdoc/node-npmdoc-styledocco)

#### Generate documentation and style guides with design patterns from stylesheets.

[![NPM](https://nodei.co/npm/styledocco.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/styledocco)

- [https://npmdoc.github.io/node-npmdoc-styledocco/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-styledocco/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-styledocco/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-styledocco/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-styledocco/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-styledocco/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "styledocco",
    "description": "Generate documentation and style guides with design patterns from stylesheets.",
    "keywords": [
        "styleguide",
        "css",
        "documentation",
        "design",
        "patterns"
    ],
    "author": "Jacob Rask <jacob@jacobrask.net>",
    "contributors": [
        "David Marrs <david@marrsbytes.com>"
    ],
    "version": "0.6.6",
    "homepage": "http://jacobrask.github.com/styledocco/",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/jacobrask/styledocco/raw/master/LICENSE"
        }
    ],
    "bugs": {
        "url": "https://github.com/jacobrask/styledocco/issues"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/jacobrask/styledocco.git"
    },
    "engines": {
        "node": ">=0.4.0"
    },
    "preferGlobal": true,
    "dependencies": {
        "async": "0.1.x",
        "clean-css": "0.4.x",
        "findit": "~1.1.0",
        "jade": "0.23.x",
        "marked": "0.2.x",
        "mkdirp": "0.x.x",
        "optimist": "0.x.x",
        "uglify-js": "1.2.x"
    },
    "devDependencies": {
        "browserify": "1.13.x",
        "jshint": "0.7.x",
        "nodeunit": "0.7.x",
        "chai": "latest",
        "mocha": "latest"
    },
    "main": "./styledocco",
    "bin": "./bin/styledocco",
    "scripts": {
        "test": "nodeunit test; mocha test"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
