# npmtest-serve-favicon

#### test coverage for  [serve-favicon (v2.4.2)](https://github.com/expressjs/serve-favicon#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-serve-favicon.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-serve-favicon) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-serve-favicon.svg)](https://travis-ci.org/npmtest/node-npmtest-serve-favicon)

#### favicon serving middleware with caching

[![NPM](https://nodei.co/npm/serve-favicon.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/serve-favicon)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-serve-favicon/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-serve-favicon/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-serve-favicon/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-serve-favicon/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-serve-favicon/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-serve-favicon/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-serve-favicon/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-serve-favicon/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-serve-favicon/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-serve-favicon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-serve-favicon/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-serve-favicon/build/test-report.html](https://npmtest.github.io/node-npmtest-serve-favicon/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-serve-favicon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-serve-favicon/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-serve-favicon/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-serve-favicon/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-serve-favicon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-serve-favicon/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-serve-favicon/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-serve-favicon/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Douglas Christopher Wilson"
    },
    "bugs": {
        "url": "https://github.com/expressjs/serve-favicon/issues"
    },
    "dependencies": {
        "etag": "~1.8.0",
        "fresh": "0.5.0",
        "ms": "1.0.0",
        "parseurl": "~1.3.1"
    },
    "description": "favicon serving middleware with caching",
    "devDependencies": {
        "eslint": "3.18.0",
        "eslint-config-standard": "7.1.0",
        "eslint-plugin-markdown": "1.0.0-beta.4",
        "eslint-plugin-promise": "3.5.0",
        "eslint-plugin-standard": "2.1.1",
        "istanbul": "0.4.5",
        "mocha": "2.5.3",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "aed1d8de67d5b83192cf31fdf53d2ea29464363e",
        "tarball": "https://registry.npmjs.org/serve-favicon/-/serve-favicon-2.4.2.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "index.js"
    ],
    "gitHead": "b450452e5dc432d9019ee48e7b4702b7ed835c10",
    "homepage": "https://github.com/expressjs/serve-favicon#readme",
    "keywords": [
        "express",
        "favicon",
        "middleware"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        }
    ],
    "name": "serve-favicon",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/serve-favicon.git"
    },
    "scripts": {
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-ci": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/"
    },
    "version": "2.4.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
