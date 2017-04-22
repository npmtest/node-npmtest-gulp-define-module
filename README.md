# npmtest-gulp-define-module

#### basic test coverage for  [gulp-define-module (v0.1.5)](https://github.com/wbyoung/gulp-define-module)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-define-module.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-define-module) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-define-module.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-define-module)

#### gulp.js plugin for creating modules

[![NPM](https://nodei.co/npm/gulp-define-module.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-define-module)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-define-module/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-define-module/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-define-module/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-define-module/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-define-module/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-define-module/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-define-module/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-define-module/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-define-module/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-define-module/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-define-module/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-define-module/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-define-module/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-define-module/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-define-module/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-define-module/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-define-module/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-define-module/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-define-module/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-define-module/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-define-module/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Whitney Young"
    },
    "bugs": {
        "url": "https://github.com/wbyoung/gulp-define-module/issues"
    },
    "dependencies": {
        "gulp-util": "^3.0.4",
        "lodash": "^3.6.0",
        "through": "^2.3.0"
    },
    "description": "gulp.js plugin for creating modules",
    "devDependencies": {
        "coveralls": "^2.11.2",
        "istanbul": "^0.3.11",
        "mocha": "^2.2.1",
        "should": "^5.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8ae57d80e9f3ed5563a0779477bca4369a4587e8",
        "tarball": "https://registry.npmjs.org/gulp-define-module/-/gulp-define-module-0.1.5.tgz"
    },
    "gitHead": "45b95a821ab13bf68255646e87c05e7b3dd5e3e0",
    "homepage": "https://github.com/wbyoung/gulp-define-module",
    "keywords": [
        "gulpplugin",
        "gulpfriendly",
        "amd",
        "commonjs",
        "node"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "wbyoung"
        }
    ],
    "name": "gulp-define-module",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/wbyoung/gulp-define-module.git"
    },
    "scripts": {
        "test": "istanbul cover ./node_modules/.bin/_mocha --report $(if [ \"$TRAVIS\" ]; then echo lcovonly; else echo html; fi) -- && if [ \"$TRAVIS\" ]; then cat ./coverage/lcov.info | ./node_modules/.bin/coveralls; fi"
    },
    "version": "0.1.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
