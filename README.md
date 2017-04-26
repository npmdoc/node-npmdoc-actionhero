# npmdoc-actionhero

#### basic api documentation for  [actionhero (v17.0.0)](http://www.actionherojs.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-actionhero.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-actionhero) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-actionhero.svg)](https://travis-ci.org/npmdoc/node-npmdoc-actionhero)

#### actionhero.js is a multi-transport API Server with integrated cluster capabilities and delayed tasks

[![NPM](https://nodei.co/npm/actionhero.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/actionhero)

- [https://npmdoc.github.io/node-npmdoc-actionhero/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-actionhero/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-actionhero/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-actionhero/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-actionhero/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-actionhero/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Evan Tahler"
    },
    "bin": {
        "actionhero": "./bin/actionhero"
    },
    "bugs": {
        "url": "https://github.com/actionhero/actionhero/issues"
    },
    "dependencies": {
        "async": "^2.1.4",
        "browser_fingerprint": "^0.1.0",
        "etag": "^1.7.0",
        "fakeredis": "^2.0.0",
        "formidable": "^1.0.17",
        "glob": "^7.1.1",
        "i18n": "^0.8.3",
        "ioredis": "^2.4.1",
        "is-running": "^2.0.1",
        "mime": "^1.3.4",
        "node-resque": "^4.0.1",
        "optimist": "^0.6.1",
        "primus": "^7.0.0",
        "qs": "^6.0.1",
        "uglify-js": "^2.8.5",
        "uuid": "^3.0.0",
        "winston": "^2.0.0",
        "ws": "^2.0.0"
    },
    "description": "actionhero.js is a multi-transport API Server with integrated cluster capabilities and delayed tasks",
    "devDependencies": {
        "chai": "^3.5.0",
        "cross-env": "^4.0.0",
        "dirty-chai": "^1.2.2",
        "mocha": "^3.2.0",
        "request": "^2.75.0",
        "standard": "^10.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "196bbce94fe45534b44124bd5f553941d5dd2e01",
        "tarball": "https://registry.npmjs.org/actionhero/-/actionhero-17.0.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "4e54d05ecf00136289bf09f73b47dca274c5d8b3",
    "homepage": "http://www.actionherojs.com",
    "keywords": [
        "api",
        "realtime",
        "socket",
        "http",
        "https",
        "web",
        "game",
        "cluster",
        "soa",
        "action",
        "task",
        "delay",
        "service",
        "tcp"
    ],
    "license": "Apache-2.0",
    "main": "actionhero.js",
    "maintainers": [
        {
            "name": "crrobinson14"
        },
        {
            "name": "davidjairala"
        },
        {
            "name": "evantahler"
        },
        {
            "name": "gcoonrod"
        }
    ],
    "name": "actionhero",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/actionhero/actionhero.git"
    },
    "scripts": {
        "help": "node ./bin/actionhero help",
        "postinstall": "echo 'To generate a new actionhero project, run \"node ./node_modules/.bin/actionhero generate\"'",
        "pretest": "standard",
        "start": "node ./bin/actionhero",
        "test": "cross-env NODE_ENV=test mocha"
    },
    "standard": {
        "ignore": [
            "bin/templates",
            "client"
        ],
        "globals": [
            "describe",
            "before",
            "beforeEach",
            "after",
            "afterEach",
            "it",
            "expect"
        ]
    },
    "version": "17.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
