# npmtest-derequire

#### basic test coverage for  [derequire (v2.0.6)](https://github.com/calvinmetcalf/derequire)  [![npm package](https://img.shields.io/npm/v/npmtest-derequire.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-derequire) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-derequire.svg)](https://travis-ci.org/npmtest/node-npmtest-derequire)

#### remove requires

[![NPM](https://nodei.co/npm/derequire.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/derequire)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-derequire/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-derequire/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-derequire/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-derequire/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-derequire/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-derequire/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-derequire/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-derequire/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-derequire/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-derequire/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-derequire/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-derequire/build/test-report.html](https://npmtest.github.io/node-npmtest-derequire/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-derequire/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-derequire/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-derequire/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-derequire/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-derequire/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-derequire/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-derequire/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-derequire/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Calvin Metcalf"
    },
    "bin": {
        "derequire": "bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/calvinmetcalf/derequire/issues"
    },
    "dependencies": {
        "acorn": "^4.0.3",
        "concat-stream": "^1.4.6",
        "escope": "^3.6.0",
        "through2": "^2.0.0",
        "yargs": "^6.5.0"
    },
    "description": "remove requires",
    "devDependencies": {
        "browserify": "^13.1.1",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "31a414bb7ca176239fa78b116636ef77d517e768",
        "tarball": "https://registry.npmjs.org/derequire/-/derequire-2.0.6.tgz"
    },
    "files": [
        "bin/cmd.js",
        "index.js",
        "plugin.js",
        "readme.md"
    ],
    "gitHead": "f06570813dbee3cfa40023f4116fb54e8b2a08af",
    "homepage": "https://github.com/calvinmetcalf/derequire",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "cwmma"
        }
    ],
    "name": "derequire",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/calvinmetcalf/derequire.git"
    },
    "scripts": {
        "perf": "node test/perf.js",
        "test": "istanbul test _mocha test/test.js"
    },
    "version": "2.0.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
