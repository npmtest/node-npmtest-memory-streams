# npmtest-memory-streams

#### test coverage for  [memory-streams (v0.1.2)](https://github.com/paulja/memory-streams-js)  [![npm package](https://img.shields.io/npm/v/npmtest-memory-streams.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-memory-streams) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-memory-streams.svg)](https://travis-ci.org/npmtest/node-npmtest-memory-streams)

#### Simple implmentation of Stream.Readable and Stream.Writable holding the data in memory.

[![NPM](https://nodei.co/npm/memory-streams.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/memory-streams)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-memory-streams/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-memory-streams/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-memory-streams/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-memory-streams/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-memory-streams/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-memory-streams/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-memory-streams/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-memory-streams/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-memory-streams/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-memory-streams/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-memory-streams/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-memory-streams/build/test-report.html](https://npmtest.github.io/node-npmtest-memory-streams/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-memory-streams/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-memory-streams/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-memory-streams/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-memory-streams/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-memory-streams/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-memory-streams/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-memory-streams/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-memory-streams/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Paul Jackson",
        "url": "http://jaaco.uk/"
    },
    "bugs": {
        "url": "https://github.com/paulja/memory-streams-js/issues"
    },
    "dependencies": {
        "readable-stream": "~1.0.2"
    },
    "description": "Simple implmentation of Stream.Readable and Stream.Writable holding the data in memory.",
    "devDependencies": {
        "should": "~1.2.2"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "273ff777ab60fec599b116355255282cca2c50c2",
        "tarball": "https://registry.npmjs.org/memory-streams/-/memory-streams-0.1.2.tgz"
    },
    "gitHead": "4c094363007f49639a04ba91bbcbf24fb32412dd",
    "homepage": "https://github.com/paulja/memory-streams-js",
    "keywords": [
        "stream",
        "string",
        "memory",
        "Readable",
        "Writable"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "paulj"
        }
    ],
    "name": "memory-streams",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/paulja/memory-streams-js.git"
    },
    "scripts": {
        "test": "node ./test/test-readablestream.js && node ./test/test-writablestream.js"
    },
    "typings": "index.d.ts",
    "version": "0.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
