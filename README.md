# npmtest-electron-osx-sign

#### basic test coverage for  [electron-osx-sign (v0.4.4)](https://github.com/electron-userland/electron-osx-sign)  [![npm package](https://img.shields.io/npm/v/npmtest-electron-osx-sign.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-electron-osx-sign) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-electron-osx-sign.svg)](https://travis-ci.org/npmtest/node-npmtest-electron-osx-sign)

#### Codesign Electron macOS apps

[![NPM](https://nodei.co/npm/electron-osx-sign.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-osx-sign)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-electron-osx-sign/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-osx-sign/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-electron-osx-sign/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-electron-osx-sign/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-electron-osx-sign/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-electron-osx-sign/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-electron-osx-sign/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-electron-osx-sign/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-electron-osx-sign/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-osx-sign/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-electron-osx-sign/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-electron-osx-sign/build/test-report.html](https://npmtest.github.io/node-npmtest-electron-osx-sign/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-electron-osx-sign/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-electron-osx-sign/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-electron-osx-sign/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-osx-sign/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-osx-sign/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-osx-sign/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-electron-osx-sign/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-electron-osx-sign/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "electron-osx-sign",
    "version": "0.4.4",
    "description": "Codesign Electron macOS apps",
    "main": "index.js",
    "bin": {
        "electron-osx-flat": "bin/electron-osx-flat.js",
        "electron-osx-sign": "bin/electron-osx-sign.js"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/electron-userland/electron-osx-sign.git"
    },
    "author": "sethlu",
    "license": "BSD-2-Clause",
    "bugs": {
        "url": "https://github.com/electron-userland/electron-osx-sign/issues"
    },
    "homepage": "https://github.com/electron-userland/electron-osx-sign",
    "dependencies": {
        "bluebird": "^3.4.7",
        "compare-version": "^0.1.2",
        "debug": "^2.6.1",
        "isbinaryfile": "^3.0.2",
        "minimist": "^1.2.0",
        "plist": "^2.0.1",
        "tempfile": "^1.1.1"
    },
    "devDependencies": {
        "electron-download": "^4.0.0",
        "eslint": "^3.16.1",
        "eslint-config-eslint": "^4.0.0",
        "extract-zip": "^1.6.0",
        "mkdirp": "^0.5.1",
        "rimraf": "^2.6.1",
        "run-series": "^1.1.4",
        "run-waterfall": "^1.1.3",
        "standard": "^8.6.0",
        "tape": "^4.6.3"
    },
    "scripts": {
        "code-standard": "standard",
        "pretest": "rimraf test/work",
        "test": "standard && tape test"
    },
    "standard": {
        "ignore": [
            "test/work"
        ]
    },
    "engines": {
        "node": ">=0.4.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
