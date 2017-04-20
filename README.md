# npmdoc-utility

#### api documentation for  [utility (v1.12.0)](https://github.com/node-modules/utility)  [![npm package](https://img.shields.io/npm/v/npmdoc-utility.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-utility) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-utility.svg)](https://travis-ci.org/npmdoc/node-npmdoc-utility)

#### A collection of useful utilities.

[![NPM](https://nodei.co/npm/utility.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/utility)

- [https://npmdoc.github.io/node-npmdoc-utility/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-utility/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-utility/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-utility/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-utility/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-utility/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "utility",
    "version": "1.12.0",
    "description": "A collection of useful utilities.",
    "main": "lib/utility.js",
    "files": [
        "lib"
    ],
    "scripts": {
        "test": "npm run lint && npm run test-local",
        "test-local": "ava test/**/*.test.js",
        "test-cov": "nyc ava test/**/*.test.js && nyc report --reporter=lcov",
        "lint": "jshint .",
        "ci": "npm run lint && npm run test-cov",
        "autod": "autod -w --prefix '~' -e benchmark",
        "test-optimized": "node --allow-natives-syntax --trace_opt --trace_deopt test/optimized.js"
    },
    "dependencies": {
        "copy-to": "~2.0.1",
        "escape-html": "~1.0.3"
    },
    "devDependencies": {
        "autod": "*",
        "ava": "^0.14.0",
        "beautify-benchmark": "*",
        "benchmark": "^2.1.0",
        "contributors": "*",
        "jshint": "*",
        "moment": "^2.12.0",
        "nyc": "6",
        "object-assign": "^4.1.1",
        "optimized": "1"
    },
    "homepage": "https://github.com/node-modules/utility",
    "repository": {
        "type": "git",
        "url": "git://github.com/node-modules/utility.git",
        "web": "https://github.com/node-modules/utility"
    },
    "keywords": [
        "utility",
        "util",
        "utils",
        "sha256",
        "sha1",
        "hash",
        "hex"
    ],
    "engines": {
        "node": ">= 0.12.0"
    },
    "author": "fengmk2 <fengmk2@gmail.com> (http://fengmk2.com)",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
