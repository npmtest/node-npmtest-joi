# npmtest-joi

#### basic test coverage for  [joi (v10.4.1)](https://github.com/hapijs/joi)  [![npm package](https://img.shields.io/npm/v/npmtest-joi.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-joi) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-joi.svg)](https://travis-ci.org/npmtest/node-npmtest-joi)

#### Object schema validation

[![NPM](https://nodei.co/npm/joi.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/joi)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-joi/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-joi/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-joi/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-joi/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-joi/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-joi/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-joi/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-joi/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-joi/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-joi/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-joi/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-joi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-joi/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-joi/build/test-report.html](https://npmtest.github.io/node-npmtest-joi/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-joi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-joi/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-joi/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-joi/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-joi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-joi/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-joi/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-joi/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/hapijs/joi/issues"
    },
    "dependencies": {
        "hoek": "4.x.x",
        "isemail": "2.x.x",
        "items": "2.x.x",
        "topo": "2.x.x"
    },
    "description": "Object schema validation",
    "devDependencies": {
        "code": "4.x.x",
        "hapitoc": "1.x.x",
        "lab": "13.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "a2fca1f0d603d1b843f2c1e086b52461f6be1f36",
        "tarball": "https://registry.npmjs.org/joi/-/joi-10.4.1.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "16b8c140fec6fc8e44caed9a9e533a76e49f5968",
    "homepage": "https://github.com/hapijs/joi",
    "keywords": [
        "hapi",
        "schema",
        "validation"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        },
        {
            "name": "marsup"
        },
        {
            "name": "nlf"
        },
        {
            "name": "wyatt"
        }
    ],
    "name": "joi",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/joi.git"
    },
    "scripts": {
        "test": "lab -t 100 -a code -L",
        "test-cov-html": "lab -r html -o coverage.html -a code",
        "test-debug": "lab -a code",
        "toc": "hapitoc",
        "version": "npm run toc && git add API.md README.md"
    },
    "version": "10.4.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
