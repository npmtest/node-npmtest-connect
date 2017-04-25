# npmtest-connect

#### basic test coverage for  [connect (v3.6.1)](https://github.com/senchalabs/connect#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-connect.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-connect) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-connect.svg)](https://travis-ci.org/npmtest/node-npmtest-connect)

#### High performance middleware framework

[![NPM](https://nodei.co/npm/connect.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/connect)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-connect/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-connect/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-connect/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-connect/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-connect/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-connect/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-connect/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-connect/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-connect/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-connect/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-connect/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-connect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-connect/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-connect/build/test-report.html](https://npmtest.github.io/node-npmtest-connect/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-connect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-connect/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-connect/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-connect/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-connect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-connect/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-connect/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-connect/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk",
        "url": "http://tjholowaychuk.com"
    },
    "bugs": {
        "url": "https://github.com/senchalabs/connect/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Jonathan Ong"
        },
        {
            "name": "Tim Caswell"
        }
    ],
    "dependencies": {
        "debug": "2.6.3",
        "finalhandler": "1.0.1",
        "parseurl": "~1.3.1",
        "utils-merge": "1.0.0"
    },
    "description": "High performance middleware framework",
    "devDependencies": {
        "istanbul": "0.4.5",
        "mocha": "3.2.0",
        "supertest": "2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b7760693a74f0454face1d9378edb3f885b43227",
        "tarball": "https://registry.npmjs.org/connect/-/connect-3.6.1.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "README.md",
        "index.js"
    ],
    "gitHead": "57cfee04a759ac81597a2e61add3795064b1c320",
    "homepage": "https://github.com/senchalabs/connect#readme",
    "keywords": [
        "framework",
        "web",
        "middleware",
        "connect",
        "rack"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "tjholowaychuk"
        }
    ],
    "name": "connect",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/senchalabs/connect.git"
    },
    "scripts": {
        "test": "mocha --require test/support/env --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --require test/support/env --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --require test/support/env --reporter spec --check-leaks test/"
    },
    "version": "3.6.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
