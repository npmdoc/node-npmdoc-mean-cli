# npmdoc-mean-cli

#### api documentation for  mean-cli (v0.12.15)  [![npm package](https://img.shields.io/npm/v/npmdoc-mean-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mean-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mean-cli.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mean-cli)

#### Simple command line interface for installing and managing MEAN apps

[![NPM](https://nodei.co/npm/mean-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mean-cli)

- [https://npmdoc.github.io/node-npmdoc-mean-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mean-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mean-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mean-cli/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mean-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mean-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "mean-cli",
    "description": "Simple command line interface for installing and managing MEAN apps",
    "version": "0.12.15",
    "author": {
        "name": "https://github.com/linnovate/mean-cli/graphs/contributors"
    },
    "bin": {
        "mean": "./bin/mean",
        "mean-init": "./bin/mean-init",
        "mean-authorize": "./bin/mean-authorize",
        "mean-whoami": "./bin/mean-whoami",
        "mean-login": "./bin/mean-login",
        "mean-addKey": "./bin/mean-addKey",
        "mean-publish": "./bin/mean-publish",
        "mean-search": "./bin/mean-search",
        "mean-register": "./bin/mean-register",
        "mean-postinstall": "./bin/mean-postinstall",
        "mean-preinstall": "./bin/mean-preinstall",
        "mean-install": "./bin/mean-install",
        "mean-uninstall": "./bin/mean-uninstall",
        "mean-docs": "./bin/mean-docs",
        "mean-package": "./bin/mean-package",
        "mean-list": "./bin/mean-list",
        "mean-status": "./bin/mean-status",
        "mean-user": "./bin/mean-user",
        "mean-logout": "./bin/mean-logout",
        "mean-disable": "./bin/mean-disable",
        "mean-enable": "./bin/mean-enable"
    },
    "contributors": "https://github.com/linnovate/mean-cli/graphs/contributors",
    "dependencies": {
        "async-series": "latest",
        "bower": "^1.3.8",
        "chalk": "^1.1.3",
        "commander": "^2.4.0",
        "crypto": "latest",
        "inquirer": "^1.0.2",
        "lodash": "^4.12.0",
        "mongoose": "~4.4.15",
        "opener": "^1.3.0",
        "progress": "^1.1.8",
        "prompt": "^1.0.0",
        "request": "^2.72.0",
        "shelljs": "^0.7.0"
    },
    "devDependencies": {
        "jshint": "^2.5.10",
        "mocha": "^2.4.5",
        "precommit-hook": "^3.0.0",
        "should": "^8.3.1"
    },
    "keywords": [
        "mean",
        "meanio",
        "mean.io",
        "mean-cli"
    ],
    "license": "MIT",
    "main": "index",
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "https://github.com/linnovate/mean-cli.git"
    },
    "scripts": {
        "test": "node node_modules/.bin/mocha test/**/*.js -R spec",
        "lint": "jshint .",
        "validate": "npm ls"
    },
    "pre-commit": [
        "lint",
        "validate",
        "test"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
