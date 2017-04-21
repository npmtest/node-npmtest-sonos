# npmtest-sonos

#### basic test coverage for  sonos (v0.14.1)  [![npm package](https://img.shields.io/npm/v/npmtest-sonos.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sonos) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sonos.svg)](https://travis-ci.org/npmtest/node-npmtest-sonos)

#### Node.js Sonos Interface

[![NPM](https://nodei.co/npm/sonos.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sonos)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sonos/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sonos/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sonos/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sonos/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sonos/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sonos/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sonos/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sonos/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sonos/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sonos/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sonos/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sonos/build/test-report.html](https://npmtest.github.io/node-npmtest-sonos/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sonos/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sonos/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sonos/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sonos/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sonos/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sonos/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sonos/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sonos/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sonos",
    "version": "0.14.1",
    "description": "Node.js Sonos Interface",
    "main": "index.js",
    "scripts": {
        "lint": "standard",
        "test": "mocha test/sonos.test.js",
        "test-onsite": "mocha test/",
        "env-run": "npm run $CMD"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/bencevans/node-sonos.git"
    },
    "keywords": [
        "sonos",
        "music",
        "control",
        "play",
        "interface"
    ],
    "author": "Ben Evans <ben@bensbit.co.uk> (http://bensbit.co.uk)",
    "contributors": [
        {
            "name": "Marshall Rose"
        },
        {
            "name": "Stephen Wan"
        }
    ],
    "license": "MIT",
    "dependencies": {
        "debug": "^2.3.3",
        "ip": "1.1.4",
        "request": "^2.79.0",
        "underscore": "1.8.3",
        "upnp-client": "0.0.1",
        "xml2js": "0.4.17"
    },
    "bugs": {
        "url": "http://github.com/bencevans/node-sonos/issues"
    },
    "devDependencies": {
        "mocha": "^3.2.0",
        "standard": "*"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
