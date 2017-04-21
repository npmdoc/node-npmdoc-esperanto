# npmdoc-esperanto

#### api documentation for  esperanto (v0.7.6)  [![npm package](https://img.shields.io/npm/v/npmdoc-esperanto.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-esperanto) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-esperanto.svg)](https://travis-ci.org/npmdoc/node-npmdoc-esperanto)

#### An easier way to convert ES6 modules to AMD and CommonJS

[![NPM](https://nodei.co/npm/esperanto.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/esperanto)

- [https://npmdoc.github.io/node-npmdoc-esperanto/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-esperanto/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-esperanto/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-esperanto/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-esperanto/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-esperanto/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "esperanto",
    "description": "An easier way to convert ES6 modules to AMD and CommonJS",
    "version": "0.7.6",
    "author": "Rich Harris",
    "repository": "https://github.com/esperantojs/esperanto",
    "license": "MIT",
    "dependencies": {
        "acorn": "^1.0.1",
        "chalk": "^1.0.0",
        "magic-string": "^0.4.9",
        "minimist": "^1.1.0",
        "sander": "^0.5.1"
    },
    "main": "dist/esperanto.js",
    "jsnext:main": "src/esperanto.js",
    "bin": {
        "esperanto": "./bin/index.js"
    },
    "devDependencies": {
        "gobble": "^0.7.2",
        "gobble-babel": "^5.1.0",
        "gobble-cli": "^0.4.2",
        "gobble-esperanto-bundle": "^0.2.0",
        "gobble-uglifyjs": "^0.1.0",
        "magic-string": "^0.6.0",
        "mocha": "^2.1.0",
        "resolve": "^1.1.0",
        "source-map": "^0.1.40",
        "source-map-support": "^0.2.10"
    },
    "files": [
        "esperanto.js",
        "src",
        "dist",
        "bin",
        "README.md"
    ],
    "scripts": {
        "build": "gobble build -f dist",
        "pretest": "npm run build",
        "test": "mocha",
        "prepublish": "npm test"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
