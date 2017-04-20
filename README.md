# npmtest-karma-spec-reporter

#### basic test coverage for  karma-spec-reporter (v0.0.31)  [![npm package](https://img.shields.io/npm/v/npmtest-karma-spec-reporter.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-karma-spec-reporter) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-karma-spec-reporter.svg)](https://travis-ci.org/npmtest/node-npmtest-karma-spec-reporter)

#### A Karma plugin. Report all spec-results to console (like mocha's spec reporter).

[![NPM](https://nodei.co/npm/karma-spec-reporter.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/karma-spec-reporter)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-karma-spec-reporter/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-karma-spec-reporter/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-karma-spec-reporter/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-karma-spec-reporter/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-karma-spec-reporter/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-karma-spec-reporter/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-karma-spec-reporter/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-karma-spec-reporter/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-karma-spec-reporter/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-karma-spec-reporter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-karma-spec-reporter/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-karma-spec-reporter/build/test-report.html](https://npmtest.github.io/node-npmtest-karma-spec-reporter/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-karma-spec-reporter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-karma-spec-reporter/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-karma-spec-reporter/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-karma-spec-reporter/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma-spec-reporter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma-spec-reporter/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-karma-spec-reporter/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-karma-spec-reporter/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "karma-spec-reporter",
    "version": "0.0.31",
    "description": "A Karma plugin. Report all spec-results to console (like mocha's spec reporter).",
    "main": "index.js",
    "scripts": {
        "test": "mocha-runner --reporter spec test/**/*.spec.js",
        "coverage": "istanbul cover -x test/**/*.js node_modules/mocha/bin/_mocha -- --reporter spec test/**/*.js",
        "precoverage-report": "run-s coverage",
        "coverage-report": "istanbul report"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/mlex/karma-spec-reporter.git"
    },
    "keywords": [
        "karma-plugin",
        "reporter"
    ],
    "author": "Michael Lex <michael.lex@codecentric.de>",
    "dependencies": {
        "colors": "^1.1.2"
    },
    "peerDependencies": {
        "karma": ">=0.9"
    },
    "license": "MIT",
    "devDependencies": {
        "chai": "^3.4.0",
        "coveralls": "^2.11.4",
        "istanbul": "^0.4.0",
        "mocha": "^3.2.0",
        "mocha-runner": "^1.1.1",
        "npm-run-all": "^4.0.2",
        "rewire": "^2.5.1",
        "sinon": "^1.17.2",
        "sinon-chai": "^2.8.0"
    },
    "files": [
        "index.js"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
