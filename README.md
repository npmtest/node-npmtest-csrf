# npmtest-csrf

#### test coverage for  [csrf (v3.0.6)](https://github.com/pillarjs/csrf#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-csrf.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-csrf) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-csrf.svg)](https://travis-ci.org/npmtest/node-npmtest-csrf)

#### primary logic behind csrf tokens

[![NPM](https://nodei.co/npm/csrf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/csrf)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-csrf/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-csrf/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-csrf/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-csrf/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-csrf/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-csrf/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-csrf/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-csrf/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-csrf/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-csrf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-csrf/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-csrf/build/test-report.html](https://npmtest.github.io/node-npmtest-csrf/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-csrf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-csrf/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-csrf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-csrf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-csrf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-csrf/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-csrf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-csrf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com"
    },
    "bugs": {
        "url": "https://github.com/pillarjs/csrf/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        }
    ],
    "dependencies": {
        "rndm": "1.2.0",
        "tsscmp": "1.0.5",
        "uid-safe": "2.1.4"
    },
    "description": "primary logic behind csrf tokens",
    "devDependencies": {
        "bluebird": "3.5.0",
        "eslint": "3.17.1",
        "eslint-config-standard": "7.0.1",
        "eslint-plugin-markdown": "1.0.0-beta.4",
        "eslint-plugin-promise": "3.5.0",
        "eslint-plugin-standard": "2.1.1",
        "istanbul": "0.4.5",
        "mocha": "2.5.3"
    },
    "directories": {},
    "dist": {
        "shasum": "b61120ddceeafc91e76ed5313bb5c0b2667b710a",
        "tarball": "https://registry.npmjs.org/csrf/-/csrf-3.0.6.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "README.md",
        "index.js"
    ],
    "gitHead": "018ec746e8ce5dea10dda78a2480a0a9e756f1a8",
    "homepage": "https://github.com/pillarjs/csrf#readme",
    "keywords": [
        "csrf",
        "tokens"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "dwolla"
        },
        {
            "name": "jongleberry"
        }
    ],
    "name": "csrf",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pillarjs/csrf.git"
    },
    "scripts": {
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --trace-deprecation --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --trace-deprecation --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --trace-deprecation --reporter spec --check-leaks test/"
    },
    "version": "3.0.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
