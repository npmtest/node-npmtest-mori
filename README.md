# npmtest-mori

#### basic test coverage for  [mori (v0.3.2)](https://github.com/swannodette/mori)  [![npm package](https://img.shields.io/npm/v/npmtest-mori.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mori) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mori.svg)](https://travis-ci.org/npmtest/node-npmtest-mori)

#### Persistent Data Structures for JavaScript

[![NPM](https://nodei.co/npm/mori.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mori)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mori/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mori/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mori/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mori/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mori/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mori/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mori/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mori/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mori/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mori/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mori/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mori/build/test-report.html](https://npmtest.github.io/node-npmtest-mori/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mori/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mori/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mori/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mori/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mori/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mori/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mori/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mori/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "mori",
    "version": "0.3.2",
    "description": "Persistent Data Structures for JavaScript",
    "homepage": "https://github.com/swannodette/mori",
    "author": "David Nolen (https://github.com/swannodette)",
    "keywords": [
        "data",
        "structure",
        "persistent",
        "clojure",
        "clojurescript",
        "map",
        "filter",
        "reduce"
    ],
    "contributors": [
        "David Nolen (https://github.com/swannodette)"
    ],
    "bugs": {
        "url": "https://github.com/swannodette/mori/issues"
    },
    "licenses": [
        {
            "type": "EPL",
            "url": "https://raw.github.com/swannodette/mori/master/epl-v10.html"
        }
    ],
    "main": "./mori.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/swannodette/mori.git"
    },
    "engines": {
        "node": ">=0.8.22"
    },
    "dependencies": {},
    "devDependencies": {
        "immutable": "3.5.0",
        "jasmine-node": "1.7.0"
    },
    "scripts": {
        "build": "./scripts/build.sh",
        "build-clean": "./scripts/build_clean.sh",
        "clean": "./scripts/clean.sh",
        "prepublish": "npm run-script build-clean",
        "docs": "./scripts/docs.sh",
        "test": "jasmine-node spec"
    },
    "directories": {
        "test": "./spec"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
