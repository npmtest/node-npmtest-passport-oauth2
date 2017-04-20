# npmtest-passport-oauth2

#### basic test coverage for  passport-oauth2 (v1.4.0)  [![npm package](https://img.shields.io/npm/v/npmtest-passport-oauth2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-passport-oauth2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-passport-oauth2.svg)](https://travis-ci.org/npmtest/node-npmtest-passport-oauth2)

#### OAuth 2.0 authentication strategy for Passport.

[![NPM](https://nodei.co/npm/passport-oauth2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/passport-oauth2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-passport-oauth2/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-oauth2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-passport-oauth2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-passport-oauth2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-passport-oauth2/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-passport-oauth2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-passport-oauth2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-passport-oauth2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-passport-oauth2/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-oauth2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-passport-oauth2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-passport-oauth2/build/test-report.html](https://npmtest.github.io/node-npmtest-passport-oauth2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-passport-oauth2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-passport-oauth2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-passport-oauth2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-passport-oauth2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-passport-oauth2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-passport-oauth2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-passport-oauth2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-passport-oauth2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "passport-oauth2",
    "version": "1.4.0",
    "description": "OAuth 2.0 authentication strategy for Passport.",
    "keywords": [
        "passport",
        "auth",
        "authn",
        "authentication",
        "authz",
        "authorization",
        "oauth",
        "oauth2"
    ],
    "author": {
        "name": "Jared Hanson",
        "url": "http://www.jaredhanson.net/"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/jaredhanson/passport-oauth2.git"
    },
    "bugs": {
        "url": "http://github.com/jaredhanson/passport-oauth2/issues"
    },
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://opensource.org/licenses/MIT"
        }
    ],
    "main": "./lib",
    "dependencies": {
        "oauth": "0.9.x",
        "passport-strategy": "1.x.x",
        "uid2": "0.0.x",
        "utils-merge": "1.x.x"
    },
    "devDependencies": {
        "make-node": "0.3.x",
        "mocha": "2.x.x",
        "chai": "2.x.x",
        "chai-passport-strategy": "1.x.x"
    },
    "engines": {
        "node": ">= 0.4.0"
    },
    "scripts": {
        "test": "node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
