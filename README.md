# api documentation for  [perfjankie (v2.1.2)](https://github.com/axemclion/perfjankie#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-perfjankie.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-perfjankie) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-perfjankie.svg)](https://travis-ci.org/npmdoc/node-npmdoc-perfjankie)
#### Browser Performance regression suite

[![NPM](https://nodei.co/npm/perfjankie.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/perfjankie)

- [https://npmdoc.github.io/node-npmdoc-perfjankie/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-perfjankie/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-perfjankie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-perfjankie/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-perfjankie/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-perfjankie/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Parashuram"
    },
    "bin": {
        "perfjankie": "lib/cli.js",
        "perfjankie-dbmigrate": "migrations/cli.js"
    },
    "bugs": {
        "url": "https://github.com/axemclion/perfjankie/issues"
    },
    "dbVersion": "0.4.0",
    "dependencies": {
        "browser-perf": "~1.4.0",
        "commander": "~2.8.1",
        "glob": "~5.0.14",
        "nano": "~6.1.5",
        "q": "~1.4.1",
        "sauce-tunnel": "^2.2.3",
        "semver": "^5.0.1",
        "serve-static": "^1.10.0"
    },
    "description": "Browser Performance regression suite",
    "devDependencies": {
        "bunyan": "~1.5.1",
        "chai": "~3.2.0",
        "chai-as-promised": "^5.1.0",
        "chromedriver": "^2.21.2",
        "dtrace-provider": "^0.6.0",
        "grunt": "~0.4.5",
        "grunt-autoprefixer": "^3.0.3",
        "grunt-connect-proxy": "^0.2.0",
        "grunt-contrib-clean": "~0.6.0",
        "grunt-contrib-concat": "^0.5.1",
        "grunt-contrib-connect": "~0.11.2",
        "grunt-contrib-copy": "^0.8.0",
        "grunt-contrib-htmlmin": "^0.4.0",
        "grunt-contrib-jshint": "~0.11.2",
        "grunt-contrib-less": "^1.0.1",
        "grunt-contrib-uglify": "^0.9.1",
        "grunt-contrib-watch": "~0.6.1",
        "grunt-mocha-test": "~0.12.7",
        "grunt-processhtml": "^0.3.8",
        "load-grunt-tasks": "~3.2.0",
        "mocha": "~2.2.5",
        "selenium-server": "^2.53.0",
        "sinon": "~1.15.4"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "9034ef20cc7390848e157c890ab2034689b6dcd6",
        "tarball": "https://registry.npmjs.org/perfjankie/-/perfjankie-2.1.2.tgz"
    },
    "gitHead": "14ae57f350d76c3452bcc9ed218787202f9ddc45",
    "homepage": "https://github.com/axemclion/perfjankie#readme",
    "keywords": [
        "browser-perf",
        "telemetry",
        "gruntplugin"
    ],
    "license": "BSD-2-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "axemclion"
        }
    ],
    "name": "perfjankie",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/axemclion/perfjankie.git"
    },
    "scripts": {
        "prepublish": "grunt clean dist",
        "test": "grunt test"
    },
    "version": "2.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
