# npmtest-regexgen

#### basic test coverage for  [regexgen (v1.2.3)](https://github.com/devongovett/regexgen#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-regexgen.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-regexgen) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-regexgen.svg)](https://travis-ci.org/npmtest/node-npmtest-regexgen)

#### Generate regular expressions that match a set of strings

[![NPM](https://nodei.co/npm/regexgen.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/regexgen)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-regexgen/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-regexgen/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-regexgen/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-regexgen/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-regexgen/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-regexgen/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-regexgen/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-regexgen/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-regexgen/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-regexgen/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-regexgen/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-regexgen/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-regexgen/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-regexgen/build/test-report.html](https://npmtest.github.io/node-npmtest-regexgen/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-regexgen/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-regexgen/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-regexgen/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-regexgen/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-regexgen/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-regexgen/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-regexgen/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-regexgen/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Devon Govett"
    },
    "bin": {
        "regexgen": "bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/devongovett/regexgen/issues"
    },
    "dependencies": {
        "jsesc": "^2.3.0",
        "regenerate": "^1.3.2"
    },
    "description": "Generate regular expressions that match a set of strings",
    "devDependencies": {
        "mocha": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7d818c1c8a89ac3edd1eac22ba45541afba125a8",
        "tarball": "https://registry.npmjs.org/regexgen/-/regexgen-1.2.3.tgz"
    },
    "engines": {
        "node": ">= 6"
    },
    "gitHead": "8f577c5b2fa3e8f371ba3ea23cd2e734cd2bdee7",
    "homepage": "https://github.com/devongovett/regexgen#readme",
    "keywords": [
        "regex",
        "trie",
        "regular",
        "expression"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "devongovett"
        }
    ],
    "name": "regexgen",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/devongovett/regexgen.git"
    },
    "runkitExample": "const regexgen = require('regexgen');\n\nregexgen(['foobar', 'foobaz', 'foozap', 'fooza']);",
    "scripts": {
        "test": "mocha"
    },
    "version": "1.2.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
