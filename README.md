# npmdoc-docker-cmd

#### api documentation for  [docker-cmd (v0.2.2)](http://github.com/iorga-group/docker-cmd)  [![npm package](https://img.shields.io/npm/v/npmdoc-docker-cmd.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-docker-cmd) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-docker-cmd.svg)](https://travis-ci.org/npmdoc/node-npmdoc-docker-cmd)

#### A Docker NodeJS lib wrapping the Docker command line and manage it from a json file.

[![NPM](https://nodei.co/npm/docker-cmd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/docker-cmd)

- [https://npmdoc.github.io/node-npmdoc-docker-cmd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-docker-cmd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-docker-cmd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-docker-cmd/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-docker-cmd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-docker-cmd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Anthony Ogier"
    },
    "bin": {
        "docker-cm": "./bin/docker-cm.js"
    },
    "bugs": {
        "url": "https://github.com/iorga-group/docker-cmd/issues"
    },
    "config": {
        "blanket": {
            "pattern": "lib/docker"
        }
    },
    "dependencies": {
        "extend": "~1.3.0",
        "minimist": "~1.1.0",
        "mstring": "~0.1.2"
    },
    "description": "A Docker NodeJS lib wrapping the Docker command line and manage it from a json file.",
    "devDependencies": {
        "blanket": "~1.1.6",
        "mocha": "~1.21.4",
        "mocha-multi": "~0.4.1",
        "mock-spawn": "~0.2.1",
        "mock-utf8-stream": "~0.1.1",
        "should": "~4.0.4",
        "sinon": "~1.10.3",
        "travis-cov": "~0.2.5"
    },
    "directories": {},
    "dist": {
        "shasum": "033db96d0c105470035337fd3284ad19d86f8166",
        "tarball": "https://registry.npmjs.org/docker-cmd/-/docker-cmd-0.2.2.tgz"
    },
    "homepage": "http://github.com/iorga-group/docker-cmd",
    "keywords": [
        "docker"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "iorga-group"
        },
        {
            "name": "anthony-o"
        }
    ],
    "name": "docker-cmd",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/iorga-group/docker-cmd.git"
    },
    "scripts": {
        "test": "multi='travis-cov=- dot=-' ./node_modules/.bin/mocha --require blanket -R mocha-multi",
        "test-html-cov-report": "mocha --require blanket -R html-cov > coverage.html"
    },
    "version": "0.2.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
