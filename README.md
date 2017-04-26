# npmtest-express-crud

#### basic test coverage for  [express-crud (v4.0.1)](https://github.com/jsdevel/node-express-crud)  [![npm package](https://img.shields.io/npm/v/npmtest-express-crud.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-crud) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-crud.svg)](https://travis-ci.org/npmtest/node-npmtest-express-crud)

#### Easy CRUD for express apps!

[![NPM](https://nodei.co/npm/express-crud.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-crud)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-crud/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-crud/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-crud/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-crud/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-crud/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-express-crud/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-express-crud/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-crud/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-crud/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-crud/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-crud/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-crud/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-crud/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-crud/build/test-report.html](https://npmtest.github.io/node-npmtest-express-crud/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-crud/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-crud/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-crud/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-crud/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-crud/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-crud/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-crud/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-crud/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Joseph Spencer"
    },
    "bugs": {
        "url": "https://github.com/jsdevel/node-express-crud/issues"
    },
    "dependencies": {
        "err-handler": "0.0.0"
    },
    "description": "Easy CRUD for express apps!",
    "devDependencies": {
        "async": "*",
        "coveralls": "~2.10.0",
        "express": "~4.4.3",
        "istanbul": "~0.2.6",
        "jshint": "~2.4.4",
        "mocha": "~1.17.1",
        "noport": "~1.0.1",
        "request": "~2.36.0",
        "should": "~3.1.3"
    },
    "directories": {},
    "dist": {
        "shasum": "5025d452eb0b143e8ed0990df6ce18b96f934098",
        "tarball": "https://registry.npmjs.org/express-crud/-/express-crud-4.0.1.tgz"
    },
    "gitHead": "e16b33c901265d3e5fce19abcb031b39183edea6",
    "homepage": "https://github.com/jsdevel/node-express-crud",
    "keywords": [
        "crud",
        "express"
    ],
    "license": "MIT",
    "main": "./lib",
    "maintainers": [
        {
            "name": "jsdevel"
        }
    ],
    "name": "express-crud",
    "optionalDependencies": {},
    "peerDependencies": {
        "express": "*",
        "async": "*"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jsdevel/node-express-crud.git"
    },
    "scripts": {
        "cover": "istanbul cover _mocha -- -R spec && cat ./coverage/lcov.info | coveralls -v && rm -rf coverage",
        "debug": "mocha --debug-brk",
        "jshint": "jshint lib && jshint --config .jshintrc-test test",
        "report": "istanbul report cobertura",
        "test": "npm run-script jshint && npm run-script cover && npm run-script report"
    },
    "version": "4.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
