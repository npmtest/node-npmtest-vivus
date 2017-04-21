# npmtest-vivus

#### basic test coverage for  [vivus (v0.4.0)](https://github.com/maxwellito/vivus)  [![npm package](https://img.shields.io/npm/v/npmtest-vivus.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vivus) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vivus.svg)](https://travis-ci.org/npmtest/node-npmtest-vivus)

#### JavaScript library to make drawing animation on SVG

[![NPM](https://nodei.co/npm/vivus.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vivus)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vivus/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vivus/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vivus/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vivus/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vivus/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vivus/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vivus/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vivus/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vivus/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vivus/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vivus/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vivus/build/test-report.html](https://npmtest.github.io/node-npmtest-vivus/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vivus/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vivus/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vivus/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vivus/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vivus/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vivus/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vivus/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vivus/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "vivus",
    "version": "0.4.0",
    "description": "JavaScript library to make drawing animation on SVG",
    "main": "dist/vivus.js",
    "scripts": {
        "test": "karma start test/karma.conf.js",
        "serve": "python -m SimpleHTTPServer 8844"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/maxwellito/vivus.git"
    },
    "author": "maxwellito",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/maxwellito/vivus/issues"
    },
    "homepage": "https://github.com/maxwellito/vivus",
    "engine": {
        "node": ">=0.10.22"
    },
    "devDependencies": {
        "gulp": "^3.8.5",
        "gulp-concat": "^2.2.0",
        "gulp-header": "^1.2.2",
        "gulp-imports": "0.0.2",
        "gulp-jshint": "^1.6.3",
        "gulp-karma": "0.0.4",
        "gulp-uglify": "^0.3.1",
        "gulp-util": "^2.2.19",
        "karma": "^0.12.17",
        "karma-chrome-launcher": "^0.1.4",
        "karma-coverage": "^0.2.6",
        "karma-jasmine": "~0.2.0"
    },
    "spm": {
        "main": "dist/vivus.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
