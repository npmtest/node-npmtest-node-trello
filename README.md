# npmtest-node-trello

#### test coverage for  [node-trello (v1.1.2)](https://github.com/adunkman/node-trello)  [![npm package](https://img.shields.io/npm/v/npmtest-node-trello.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-trello) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-trello.svg)](https://travis-ci.org/npmtest/node-npmtest-node-trello)

#### Node wrapper for Trello's HTTP API.

[![NPM](https://nodei.co/npm/node-trello.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-trello)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-trello/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-trello/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-trello/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-trello/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-trello/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-trello/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-trello/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-trello/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-trello/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-trello/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-trello/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-trello/build/test-report.html](https://npmtest.github.io/node-npmtest-node-trello/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-trello/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-trello/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-trello/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-trello/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-trello/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-trello/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-trello/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-trello/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Luca Matteis"
    },
    "bugs": {
        "url": "http://github.com/adunkman/node-trello/issues"
    },
    "config": {
        "travis-cov": {
            "threshold": 75
        },
        "blanket": {
            "pattern": "//^((?!/node_modules/)(?!/test/).)*$/ig"
        }
    },
    "contributors": [
        {
            "name": "Andrew Dunkman"
        }
    ],
    "dependencies": {
        "oauth": "0.9.7",
        "request": "2.51.0"
    },
    "description": "Node wrapper for Trello's HTTP API.",
    "devDependencies": {
        "blanket": "1.1.6",
        "mocha": "2.1.0",
        "should": "5.1.0",
        "travis-cov": "0.2.5"
    },
    "directories": {},
    "dist": {
        "shasum": "7276155d69d9c9f493b2d6119704d84e37171187",
        "tarball": "https://registry.npmjs.org/node-trello/-/node-trello-1.1.2.tgz"
    },
    "engines": [
        "node >= 0.6.17"
    ],
    "gitHead": "fe60c6426bdd858f1019f115ca523cf595350891",
    "homepage": "https://github.com/adunkman/node-trello",
    "keywords": [
        "http",
        "trello",
        "api",
        "web-service"
    ],
    "main": "./index",
    "maintainers": [
        {
            "name": "lmatteis"
        },
        {
            "name": "adunkman"
        }
    ],
    "name": "node-trello",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/adunkman/node-trello.git"
    },
    "scripts": {
        "test": "mocha --reporter spec && ./node_modules/.bin/mocha --require blanket --reporter travis-cov",
        "test-cov-report": "mocha --require blanket --reporter html-cov > coverage.html && open coverage.html"
    },
    "version": "1.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
