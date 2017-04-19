# npmtest-lmd

#### test coverage for  [lmd (v1.13.4)](http://lmdjs.org/)  [![npm package](https://img.shields.io/npm/v/npmtest-lmd.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lmd) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lmd.svg)](https://travis-ci.org/npmtest/node-npmtest-lmd)

#### LMD: Lazy Module Declaration

[![NPM](https://nodei.co/npm/lmd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lmd)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lmd/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lmd/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lmd/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lmd/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lmd/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lmd/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lmd/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-lmd/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-lmd/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lmd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-lmd/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-lmd/build/test-report.html](https://npmtest.github.io/node-npmtest-lmd/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-lmd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lmd/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-lmd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lmd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lmd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lmd/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lmd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lmd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mikhail Davydov"
    },
    "bin": {
        "lmd": "./bin/lmd"
    },
    "bugs": {
        "url": "https://github.com/azproduction/lmd/issues"
    },
    "contributors": [
        {
            "name": "Mikhail Davydov",
            "url": "http://azproduction.ru/"
        },
        {
            "name": "texnikru",
            "url": "https://github.com/texnikru"
        },
        {
            "name": "Leonid Borisenko",
            "url": "https://github.com/leonidborisenko"
        },
        {
            "name": "Ivan ant-hill",
            "url": "https://github.com/ant-hill"
        },
        {
            "name": "Jonathan Dumaine",
            "url": "http://www.jonathan-dumaine.com/"
        },
        {
            "name": "Alexander Myadzel",
            "url": "http://twitter.com/thenameisbusy"
        },
        {
            "name": "Maxceem",
            "url": "https://github.com/Maxceem"
        },
        {
            "name": "Denis Chistyakov",
            "url": "http://disachist.ya.ru"
        },
        {
            "name": "alnikitich",
            "url": "https://github.com/alnikitich"
        },
        {
            "name": "Egor Halimonenko",
            "url": "http://h123.ru"
        },
        {
            "name": "kastigar",
            "url": "https://github.com/kastigar"
        },
        {
            "name": "Vadim Budarin"
        },
        {
            "name": "Evgeniy Solodukhin"
        },
        {
            "name": "Alexey Ivanov"
        },
        {
            "name": "generalov",
            "url": "https://github.com/generalov"
        }
    ],
    "dependencies": {
        "colors": "0.6.0-1",
        "csso": "~1.3.10",
        "express": "2.5.9",
        "glob": "~3.1.14",
        "jade": "0.26.1",
        "lodash-template": "1.0.0",
        "optimist": "~0.3.5",
        "readable-stream": "~1.0.0",
        "source-map": "~0.1.3",
        "uglify-js": "1.3.4"
    },
    "description": "LMD: Lazy Module Declaration",
    "devDependencies": {
        "chai": "*",
        "colors": "~0.6.0",
        "http-server": "~0.5.1",
        "mocha": "1.11.0",
        "phantomjs": "1.9.16",
        "vow": "0.3.12"
    },
    "directories": {},
    "dist": {
        "shasum": "42963efcb842c86294552f45043f1af8f84ab573",
        "tarball": "https://registry.npmjs.org/lmd/-/lmd-1.13.4.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "03410c36839728de683c697670e1b205dc8193ee",
    "homepage": "http://lmdjs.org/",
    "keywords": [
        "lmd",
        "amd",
        "module",
        "components",
        "styles",
        "builder",
        "optimizer",
        "cli",
        "tool"
    ],
    "license": "MIT",
    "main": "./bin/lmd_builder.js",
    "maintainers": [
        {
            "name": "azproduction"
        }
    ],
    "name": "lmd",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/azproduction/lmd.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "1.13.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
