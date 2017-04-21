# npmtest-get-pixels

#### basic test coverage for  get-pixels (v3.3.0)  [![npm package](https://img.shields.io/npm/v/npmtest-get-pixels.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-get-pixels) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-get-pixels.svg)](https://travis-ci.org/npmtest/node-npmtest-get-pixels)

#### Reads the pixels of an image as an ndarray

[![NPM](https://nodei.co/npm/get-pixels.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/get-pixels)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-get-pixels/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-get-pixels/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-get-pixels/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-get-pixels/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-get-pixels/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-get-pixels/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-get-pixels/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-get-pixels/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-get-pixels/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-get-pixels/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-get-pixels/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-get-pixels/build/test-report.html](https://npmtest.github.io/node-npmtest-get-pixels/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-get-pixels/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-get-pixels/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-get-pixels/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-get-pixels/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-get-pixels/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-get-pixels/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-get-pixels/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-get-pixels/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "get-pixels",
    "version": "3.3.0",
    "description": "Reads the pixels of an image as an ndarray",
    "main": "node-pixels.js",
    "directories": {
        "test": "test"
    },
    "dependencies": {
        "ndarray": "^1.0.13",
        "pngjs": "^2.0.0",
        "ndarray-pack": "^1.1.1",
        "jpeg-js": "^0.1.1",
        "omggif": "^1.0.5",
        "node-bitmap": "0.0.1",
        "through": "^2.3.4",
        "request": "^2.44.0",
        "parse-data-uri": "^0.2.0",
        "mime-types": "^2.0.1",
        "data-uri-to-buffer": "0.0.3"
    },
    "devDependencies": {
        "tape": "^2.12.3",
        "brfs": "^1.2.0",
        "browserify": "^3.44.0",
        "beefy": "^1.1.0"
    },
    "scripts": {
        "test": "tap test/*.js",
        "test-browser": "beefy test/test.js --open  -- -t brfs"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/scijs/get-pixels.git"
    },
    "keywords": [
        "ndarray",
        "pixel",
        "get",
        "read",
        "pixel",
        "image",
        "png",
        "jpeg",
        "jpg",
        "jpe",
        "gif",
        "decode",
        "buffer",
        "data",
        "parse",
        "dom",
        "node",
        "browserify"
    ],
    "browser": "dom-pixels.js",
    "author": "Mikola Lysenko",
    "license": "MIT",
    "readmeFilename": "README.md",
    "gitHead": "380bbda330666e4a4066c48ef5a42770d13bcd5c"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
