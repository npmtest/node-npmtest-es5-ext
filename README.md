# test coverage for  [es5-ext (v0.10.15)](https://github.com/medikoo/es5-ext#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-es5-ext.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-es5-ext) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-es5-ext.svg)](https://travis-ci.org/npmtest/node-npmtest-es5-ext)
#### ECMAScript extensions and shims

[![NPM](https://nodei.co/npm/es5-ext.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/es5-ext)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-es5-ext/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-es5-ext/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-es5-ext/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-es5-ext/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-es5-ext/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-es5-ext/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-es5-ext/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-es5-ext/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-es5-ext/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-es5-ext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-es5-ext/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-es5-ext/build/test-report.html](https://npmtest.github.io/node-npmtest-es5-ext/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-es5-ext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-es5-ext/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-es5-ext/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-es5-ext/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-es5-ext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-es5-ext/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-es5-ext/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-es5-ext/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mariusz Nowak",
        "url": "http://www.medikoo.com/"
    },
    "bugs": {
        "url": "https://github.com/medikoo/es5-ext/issues"
    },
    "dependencies": {
        "es6-iterator": "2",
        "es6-symbol": "~3.1"
    },
    "description": "ECMAScript extensions and shims",
    "devDependencies": {
        "tad": "~0.2.7",
        "xlint": "~0.2.2",
        "xlint-jslint-medikoo": "~0.1.4"
    },
    "directories": {},
    "dist": {
        "shasum": "c330a5934c1ee21284a7c081a86e5fd937c91ea6",
        "tarball": "https://registry.npmjs.org/es5-ext/-/es5-ext-0.10.15.tgz"
    },
    "gitHead": "51091920f5e4bec719702011c358fb4a24b2e998",
    "homepage": "https://github.com/medikoo/es5-ext#readme",
    "keywords": [
        "ecmascript",
        "ecmascript5",
        "ecmascript6",
        "es5",
        "es6",
        "extensions",
        "ext",
        "addons",
        "extras",
        "harmony",
        "javascript",
        "polyfill",
        "shim",
        "util",
        "utils",
        "utilities"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "medikoo"
        }
    ],
    "name": "es5-ext",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/medikoo/es5-ext.git"
    },
    "scripts": {
        "lint": "node node_modules/xlint/bin/xlint --linter=node_modules/xlint-jslint-medikoo/index.js --no-cache --no-stream",
        "lint-console": "node node_modules/xlint/bin/xlint --linter=node_modules/xlint-jslint-medikoo/index.js --watch",
        "test": "node ./node_modules/tad/bin/tad"
    },
    "version": "0.10.15"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
