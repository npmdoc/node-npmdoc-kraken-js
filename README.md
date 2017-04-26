# npmdoc-kraken-js

#### basic api documentation for  [kraken-js (v2.1.0)](https://github.com/krakenjs/kraken-js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-kraken-js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-kraken-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-kraken-js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-kraken-js)

#### An express-based Node.js web application bootstrapping module.

[![NPM](https://nodei.co/npm/kraken-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/kraken-js)

- [https://npmdoc.github.io/node-npmdoc-kraken-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-kraken-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-kraken-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-kraken-js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-kraken-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-kraken-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Erik Toth"
    },
    "bugs": {
        "url": "https://github.com/krakenjs/kraken-js/issues"
    },
    "contributors": [
        {
            "name": "Jeff Harrell"
        },
        {
            "name": "Trevor Livingston"
        },
        {
            "name": "Lenny Markus"
        },
        {
            "name": "Jean-Charles Sisk"
        }
    ],
    "dependencies": {
        "bluebird": "^2.9.24",
        "body-parser": "^1.12.2",
        "caller": "^1.0.0",
        "compression": "^1.4.3",
        "confit": "^2.0.3",
        "cookie-parser": "^1.3.4",
        "core-util-is": "^1.0.1",
        "debuglog": "^1.0.1",
        "depd": "^1.0.1",
        "endgame": "^1.0.0",
        "express-enrouten": "^1.2.0",
        "express-session": "^1.10.4",
        "formidable": "^1.0.17",
        "lusca": "^1.0.3",
        "meddleware": "^3.0.2",
        "morgan": "^1.5.2",
        "serve-favicon": "^2.2.0",
        "serve-static": "^1.9.2",
        "shortstop": "^1.0.1",
        "shortstop-handlers": "^1.0.0",
        "shortstop-resolve": "^1.0.1",
        "shush": "^1.0.0"
    },
    "description": "An express-based Node.js web application bootstrapping module.",
    "devDependencies": {
        "consolidate": "^0.12.1",
        "dustjs-linkedin": "^2.6.2",
        "ejs": "^2.3.1",
        "express": "^4.8.4",
        "istanbul": "^0.3.13",
        "jade": "^1.9.2",
        "jshint": "^2.6.3",
        "supertest": "^0.15.0",
        "tape": "^4.0.0"
    },
    "directories": {
        "example": "./example",
        "lib": "./lib",
        "test": "./test"
    },
    "dist": {
        "shasum": "7eef061f8153972f05e726a8b64032dbaea2e805",
        "tarball": "https://registry.npmjs.org/kraken-js/-/kraken-js-2.1.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "9bf2e97154292cd9d50e6fcbe8f6cdf793b3d588",
    "homepage": "https://github.com/krakenjs/kraken-js#readme",
    "keywords": [
        "node.js",
        "node",
        "javascript",
        "js",
        "web",
        "express",
        "connect"
    ],
    "licenses": [
        {
            "type": "Apache 2.0",
            "url": "http://www.apache.org/licenses/LICENSE-2.0.html"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "totherik"
        },
        {
            "name": "jeffharrell"
        },
        {
            "name": "pvenkatakrishnan"
        },
        {
            "name": "jasisk"
        }
    ],
    "name": "kraken-js",
    "optionalDependencies": {},
    "peerDependencies": {
        "express": "^4.8.4"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/krakenjs/kraken-js.git"
    },
    "scripts": {
        "cover": "istanbul cover tape -- test/*.js",
        "lint": "jshint -c .jshintrc index.js lib/ middleware/",
        "test": "tape test/*.js"
    },
    "version": "2.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
