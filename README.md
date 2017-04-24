# npmtest-grunt-contrib-nodeunit

#### basic test coverage for  [grunt-contrib-nodeunit (v1.0.0)](https://github.com/gruntjs/grunt-contrib-nodeunit#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-contrib-nodeunit.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-contrib-nodeunit) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-contrib-nodeunit.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-contrib-nodeunit)

#### Run Nodeunit unit tests

[![NPM](https://nodei.co/npm/grunt-contrib-nodeunit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-contrib-nodeunit)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-contrib-nodeunit/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-contrib-nodeunit/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-contrib-nodeunit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-contrib-nodeunit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-contrib-nodeunit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-contrib-nodeunit/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-contrib-nodeunit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "appveyor_id": "8526qwiyaavbfbxh",
    "author": {
        "name": "Grunt Team",
        "url": "http://gruntjs.com/"
    },
    "bugs": {
        "url": "https://github.com/gruntjs/grunt-contrib-nodeunit/issues"
    },
    "contributors": [
        {
            "name": "\"Cowboy\" Ben Alman",
            "url": "http://benalman.com"
        },
        {
            "name": "Tyler Kellen",
            "url": "http://goingslowly.com"
        },
        {
            "name": "Kyle Robinson Young",
            "url": "http://dontkry.com"
        },
        {
            "name": "Vlad Filippov",
            "url": "http://vladfilippov.com"
        },
        {
            "name": "Tim Wood",
            "url": "http://timwoodcreates.com"
        },
        {
            "name": "Nic Jansma",
            "url": "http://nicj.net"
        },
        {
            "name": "Matthew Beale",
            "url": "http://madhatted.com"
        }
    ],
    "dependencies": {
        "nodeunit": "^0.9.0"
    },
    "description": "Run Nodeunit unit tests",
    "devDependencies": {
        "grunt": "^0.4.5",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-clean": "^0.6.0",
        "grunt-contrib-internal": "^0.4.12",
        "grunt-contrib-jshint": "^0.11.0",
        "tap": "^0.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "6f488555ed9c0c8478854103c71edb1fc4685f05",
        "tarball": "https://registry.npmjs.org/grunt-contrib-nodeunit/-/grunt-contrib-nodeunit-1.0.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "tasks"
    ],
    "gitHead": "d0288a2b0b816094e76b7ac73331d04612afd79c",
    "homepage": "https://github.com/gruntjs/grunt-contrib-nodeunit#readme",
    "keywords": [
        "gruntplugin",
        "nodeunit",
        "test",
        "runner"
    ],
    "license": "MIT",
    "main": "tasks/nodeunit.js",
    "maintainers": [
        {
            "name": "tkellen"
        },
        {
            "name": "cowboy"
        },
        {
            "name": "shama"
        },
        {
            "name": "vladikoff"
        },
        {
            "name": "sindresorhus"
        },
        {
            "name": "jmeas"
        }
    ],
    "name": "grunt-contrib-nodeunit",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gruntjs/grunt-contrib-nodeunit.git"
    },
    "scripts": {
        "test": "grunt test && grunt jshint"
    },
    "version": "1.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
