# npmtest-gulp-ttf2woff

#### basic test coverage for  [gulp-ttf2woff (v1.1.0)](https://github.com/nfroidure/gulp-ttf2woff)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-ttf2woff.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-ttf2woff) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-ttf2woff.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-ttf2woff)

#### Create a WOFF font from a TTF one

[![NPM](https://nodei.co/npm/gulp-ttf2woff.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-ttf2woff)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-ttf2woff/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-ttf2woff/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-ttf2woff/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-ttf2woff/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-ttf2woff/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-ttf2woff/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-ttf2woff/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-ttf2woff/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-ttf2woff/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-ttf2woff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-ttf2woff/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-ttf2woff/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-ttf2woff/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-ttf2woff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-ttf2woff/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-ttf2woff/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-ttf2woff/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-ttf2woff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-ttf2woff/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-ttf2woff/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-ttf2woff/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nicolas Froidure",
        "url": "http://www.insertafter.com/blog.html"
    },
    "bugs": {
        "url": "https://github.com/nfroidure/gulp-ttf2woff/issues"
    },
    "dependencies": {
        "bufferstreams": "^1.0.2",
        "gulp-util": "^3.0.6",
        "readable-stream": "^2.0.1",
        "ttf2woff": "^1.3.0"
    },
    "description": "Create a WOFF font from a TTF one",
    "devDependencies": {
        "coveralls": "^2.11.2",
        "gulp": "^3.9.0",
        "istanbul": "^0.3.16",
        "mocha": "^2.2.5",
        "mocha-lcov-reporter": "^0.0.2",
        "streamtest": "^1.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "3a2ede53158f02a6323fd6f4dba008b2eb30ba5b",
        "tarball": "https://registry.npmjs.org/gulp-ttf2woff/-/gulp-ttf2woff-1.1.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "475e019937e6f05d2803d52c52763186d318b89f",
    "homepage": "https://github.com/nfroidure/gulp-ttf2woff",
    "keywords": [
        "gulpplugin",
        "gulp",
        "gulp-plugin",
        "font",
        "woff",
        "ttf",
        "converter"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/nfroidure/gulp-ttf2woff/blob/master/LICENSE"
        }
    ],
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "nfroidure"
        }
    ],
    "name": "gulp-ttf2woff",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/nfroidure/gulp-ttf2woff.git"
    },
    "scripts": {
        "cover": "./node_modules/istanbul/lib/cli.js cover --report html ./node_modules/mocha/bin/_mocha -- tests/*.mocha.js -R spec -t 5000",
        "coveralls": "./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha --report lcovonly -- tests/*.mocha.js -R spec -t 5000 && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "test": "mocha tests/*.mocha.js"
    },
    "version": "1.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
