# npmtest-njwt

#### test coverage for  [njwt (v0.4.0)](https://github.com/jwtk/njwt)  [![npm package](https://img.shields.io/npm/v/npmtest-njwt.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-njwt) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-njwt.svg)](https://travis-ci.org/npmtest/node-npmtest-njwt)

#### JWT Library for Node.js

[![NPM](https://nodei.co/npm/njwt.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/njwt)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-njwt/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-njwt/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-njwt/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-njwt/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-njwt/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-njwt/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-njwt/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-njwt/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-njwt/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-njwt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-njwt/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-njwt/build/test-report.html](https://npmtest.github.io/node-npmtest-njwt/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-njwt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-njwt/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-njwt/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-njwt/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-njwt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-njwt/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-njwt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-njwt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stormpath, Inc."
    },
    "bugs": {
        "url": "https://github.com/jwtk/njwt/issues"
    },
    "dependencies": {
        "ecdsa-sig-formatter": "^1.0.5",
        "uuid": "^2.0.1"
    },
    "description": "JWT Library for Node.js",
    "devDependencies": {
        "chai": "^2.2.0",
        "coveralls": "^2.11.15",
        "istanbul": "^0.4.5",
        "jsonwebtoken": "^5.0.2",
        "jwt-simple": "^0.3.0",
        "mocha": "^3.2.0",
        "secure-random": "^1.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "7324ed9d76a9d54b5e265cb7b6a3c55f146fd3c7",
        "tarball": "https://registry.npmjs.org/njwt/-/njwt-0.4.0.tgz"
    },
    "gitHead": "3bc7df1fa56fa139d1070e288152a5fd3d41c44a",
    "homepage": "https://github.com/jwtk/njwt",
    "keywords": [
        "jwt"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "robertjd"
        },
        {
            "name": "lhazlewood"
        }
    ],
    "name": "njwt",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jwtk/njwt.git"
    },
    "scripts": {
        "test": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly test/ -- -R spec --no-timeouts; cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js; rm -rf ./coverage",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --timeout=5000 --reporter dot --check-leaks test/",
        "test-debug": "mocha --timeout=5000 --debug --reporter dot --check-leaks -w ./*.js test/ ",
        "test-watch": "mocha --timeout=5000 --reporter dot --check-leaks -w ./*.js test/ "
    },
    "version": "0.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
