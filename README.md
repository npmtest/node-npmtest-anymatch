# test coverage for  [anymatch (v1.3.0)](https://github.com/es128/anymatch)  [![npm package](https://img.shields.io/npm/v/npmtest-anymatch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-anymatch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-anymatch.svg)](https://travis-ci.org/npmtest/node-npmtest-anymatch)
#### Matches strings against configurable strings, globs, regular expressions, and/or functions

[![NPM](https://nodei.co/npm/anymatch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/anymatch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-anymatch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-anymatch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-anymatch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-anymatch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-anymatch/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-anymatch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-anymatch/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-anymatch/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-anymatch/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-anymatch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-anymatch/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-anymatch/build/test-report.html](https://npmtest.github.io/node-npmtest-anymatch/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-anymatch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-anymatch/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-anymatch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-anymatch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-anymatch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-anymatch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-anymatch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-anymatch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Elan Shanker",
        "url": "http://github.com/es128"
    },
    "bugs": {
        "url": "https://github.com/es128/anymatch/issues"
    },
    "dependencies": {
        "arrify": "^1.0.0",
        "micromatch": "^2.1.5"
    },
    "description": "Matches strings against configurable strings, globs, regular expressions, and/or functions",
    "devDependencies": {
        "coveralls": "^2.11.2",
        "istanbul": "^0.3.13",
        "mocha": "^2.2.4"
    },
    "directories": {},
    "dist": {
        "shasum": "a3e52fa39168c825ff57b0248126ce5a8ff95507",
        "tarball": "https://registry.npmjs.org/anymatch/-/anymatch-1.3.0.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "253d2ad42f644ed18557f561312a7f8426daca84",
    "homepage": "https://github.com/es128/anymatch",
    "keywords": [
        "match",
        "any",
        "string",
        "file",
        "fs",
        "list",
        "glob",
        "regex",
        "regexp",
        "regular",
        "expression",
        "function"
    ],
    "license": "ISC",
    "maintainers": [
        {
            "name": "es128"
        }
    ],
    "name": "anymatch",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/es128/anymatch.git"
    },
    "scripts": {
        "test": "istanbul cover _mocha && cat ./coverage/lcov.info | coveralls"
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
