# npmtest-striptags

#### basic test coverage for  [striptags (v3.0.1)](https://github.com/ericnorris/striptags)  [![npm package](https://img.shields.io/npm/v/npmtest-striptags.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-striptags) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-striptags.svg)](https://travis-ci.org/npmtest/node-npmtest-striptags)

#### PHP strip_tags in Node.js

[![NPM](https://nodei.co/npm/striptags.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/striptags)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-striptags/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-striptags/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-striptags/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-striptags/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-striptags/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-striptags/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-striptags/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-striptags/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-striptags/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-striptags/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-striptags/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-striptags/build/test-report.html](https://npmtest.github.io/node-npmtest-striptags/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-striptags/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-striptags/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-striptags/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-striptags/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-striptags/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-striptags/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-striptags/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-striptags/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "striptags",
    "description": "PHP strip_tags in Node.js",
    "license": "MIT",
    "author": "Eric Norris (https://github.com/ericnorris)",
    "repository": {
        "type": "git",
        "url": "https://github.com/ericnorris/striptags.git"
    },
    "main": "src/striptags.js",
    "homepage": "https://github.com/ericnorris/striptags",
    "bugs": "https://github.com/ericnorris/striptags/issues",
    "version": "3.0.1",
    "devDependencies": {
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0"
    },
    "keywords": [
        "striptags",
        "strip_tags",
        "html",
        "strip",
        "tags"
    ],
    "scripts": {
        "test": "mocha",
        "coverage": "istanbul cover _mocha -- -R spec"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
