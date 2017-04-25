# npmtest-pm2-meteor

#### basic test coverage for  [pm2-meteor (v0.4.1)](https://github.com/andruschka/pm2-meteor)  [![npm package](https://img.shields.io/npm/v/npmtest-pm2-meteor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pm2-meteor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pm2-meteor.svg)](https://travis-ci.org/npmtest/node-npmtest-pm2-meteor)

#### Simplest way to deploy, scale and run Meteor Apps with PM2.

[![NPM](https://nodei.co/npm/pm2-meteor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pm2-meteor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pm2-meteor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pm2-meteor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pm2-meteor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pm2-meteor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pm2-meteor/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-pm2-meteor/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-pm2-meteor/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pm2-meteor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pm2-meteor/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pm2-meteor/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pm2-meteor/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pm2-meteor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pm2-meteor/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pm2-meteor/build/test-report.html](https://npmtest.github.io/node-npmtest-pm2-meteor/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pm2-meteor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pm2-meteor/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pm2-meteor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pm2-meteor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pm2-meteor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pm2-meteor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pm2-meteor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pm2-meteor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "andruschka",
        "url": "http://github.com/andruschka"
    },
    "bin": {
        "pm2-meteor": "lib/program.js"
    },
    "bugs": {
        "url": "https://github.com/andruschka/pm2-meteor/issues"
    },
    "dependencies": {
        "abs": "^1.0.0",
        "async": "^1.4.2",
        "cli": "^0.11.0",
        "commander": "^2.9.0",
        "nodemiral": "^1.1.1"
    },
    "description": "Simplest way to deploy, scale and run Meteor Apps with PM2.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "3ac1fe591564fb8fb8ee301490496dc7001b9cde",
        "tarball": "https://registry.npmjs.org/pm2-meteor/-/pm2-meteor-0.4.1.tgz"
    },
    "gitHead": "cb987fee25eb254d9e725497d5d722b9d9e40d1e",
    "homepage": "https://github.com/andruschka/pm2-meteor",
    "keywords": [
        "pm2",
        "meteor",
        "config",
        "deploy",
        "deployment",
        "meteorite",
        "git deployment",
        "nodejs",
        "nvm"
    ],
    "license": "MIT",
    "main": "lib/pm2-meteor.js",
    "maintainers": [
        {
            "name": "andruschka"
        }
    ],
    "name": "pm2-meteor",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/andruschka/pm2-meteor.git"
    },
    "scripts": {
        "build": "make build",
        "prepublish": "make build"
    },
    "version": "0.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
