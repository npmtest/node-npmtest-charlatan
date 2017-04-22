# npmtest-charlatan

#### basic test coverage for  [charlatan (v1.1.0)](https://github.com/nodeca/charlatan)  [![npm package](https://img.shields.io/npm/v/npmtest-charlatan.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-charlatan) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-charlatan.svg)](https://travis-ci.org/npmtest/node-npmtest-charlatan)

#### Fake identities generator for node.js (names, addresses, phones, IPs and others). Supports multiple languages.

[![NPM](https://nodei.co/npm/charlatan.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/charlatan)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-charlatan/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-charlatan/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-charlatan/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-charlatan/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-charlatan/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-charlatan/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-charlatan/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-charlatan/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-charlatan/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-charlatan/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-charlatan/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-charlatan/build/test-report.html](https://npmtest.github.io/node-npmtest-charlatan/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-charlatan/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-charlatan/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-charlatan/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-charlatan/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-charlatan/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-charlatan/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-charlatan/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-charlatan/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eugene Shkuropat"
    },
    "browser": {
        "./lib/locales.js": "./lib/locales_browser.js",
        "./lib/charlatan/bitcoin.js": false
    },
    "bugs": {
        "url": "https://github.com/nodeca/charlatan/issues"
    },
    "dependencies": {
        "js-yaml": "^3.2.7"
    },
    "description": "Fake identities generator for node.js (names, addresses, phones, IPs and others). Supports multiple languages.",
    "devDependencies": {
        "eslint": "3.5.0",
        "istanbul": "^0.4.5",
        "mersenne-twister": "1",
        "mocha": "^3.0.2",
        "ndoc": "^5.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "58b5e39e91e9b28009aaee08a930700b7e94582b",
        "tarball": "https://registry.npmjs.org/charlatan/-/charlatan-1.1.0.tgz"
    },
    "files": [
        "index.js",
        "lib/"
    ],
    "gitHead": "d458e093763ed9dc032c79b404e79ad683e8f248",
    "homepage": "https://github.com/nodeca/charlatan",
    "keywords": [
        "charlatan",
        "faker",
        "fake",
        "dummy",
        "identity",
        "test"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "vitaly"
        }
    ],
    "name": "charlatan",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nodeca/charlatan.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "1.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
