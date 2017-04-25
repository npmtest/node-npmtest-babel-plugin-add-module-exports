# npmtest-babel-plugin-add-module-exports

#### basic test coverage for  [babel-plugin-add-module-exports (v0.2.1)](https://github.com/59naga/babel-plugin-add-module-exports#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-babel-plugin-add-module-exports.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-babel-plugin-add-module-exports) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-babel-plugin-add-module-exports.svg)](https://travis-ci.org/npmtest/node-npmtest-babel-plugin-add-module-exports)

#### Fix babel/babel#2212

[![NPM](https://nodei.co/npm/babel-plugin-add-module-exports.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babel-plugin-add-module-exports)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-babel-plugin-add-module-exports/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-babel-plugin-add-module-exports/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/build/test-report.html](https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-babel-plugin-add-module-exports/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-babel-plugin-add-module-exports/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babel-plugin-add-module-exports/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babel-plugin-add-module-exports/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-babel-plugin-add-module-exports/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "abigail": {
        "plugins": {
            "log": false,
            "parse": "raw",
            "watch": false
        }
    },
    "author": {
        "name": "59naga",
        "url": "http://berabou.me"
    },
    "bugs": {
        "url": "https://github.com/59naga/babel-plugin-add-module-exports/issues"
    },
    "dependencies": {},
    "description": "Fix babel/babel#2212",
    "devDependencies": {
        "abigail": "^1.6.1",
        "babel-cli": "^6.5.1",
        "babel-core": "^6.5.1",
        "babel-plugin-transform-export-extensions": "^6.5.0",
        "babel-preset-es2015": "^6.5.0",
        "babel-preset-power-assert": "^1.0.0",
        "chokidar": "^1.4.3",
        "codeclimate-test-reporter": "^0.3.1",
        "eslint": "^2.8.0",
        "eslint-config-standard": "^5.1.0",
        "eslint-plugin-mocha": "^2.2.0",
        "eslint-plugin-promise": "^1.1.0",
        "eslint-plugin-standard": "^1.3.1",
        "mocha": "^2.4.5",
        "npm-statement": "^0.0.0",
        "nyc": "^6.4.0",
        "power-assert": "^1.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9ae9a1f4a8dc67f0cdec4f4aeda1e43a5ff65e25",
        "tarball": "https://registry.npmjs.org/babel-plugin-add-module-exports/-/babel-plugin-add-module-exports-0.2.1.tgz"
    },
    "files": [
        "lib"
    ],
    "gitHead": "aa37f68bb570042f57e7213c014fa04e8ff5e59b",
    "homepage": "https://github.com/59naga/babel-plugin-add-module-exports#readme",
    "keywords": [
        "babel-plugin",
        "module.exports"
    ],
    "license": "MIT",
    "main": "lib",
    "maintainers": [
        {
            "name": "59naga"
        },
        {
            "name": "lijunle"
        }
    ],
    "name": "babel-plugin-add-module-exports",
    "nyc": {
        "exclude": [
            "spec"
        ]
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/59naga/babel-plugin-add-module-exports.git"
    },
    "scripts": {
        "build": "abby compile --log --env",
        "compile": "abby compile:* --parse serial",
        "compile:copy": "cp test/spec.js spec/spec.js",
        "compile:src": "babel src --out-dir lib --source-maps",
        "compile:test": "babel test --out-dir spec --ignore test/spec.js",
        "compile:version": "babel -V",
        "cover": "abby cover:* --parse serial --launch force",
        "cover:report": "npm-if TRAVIS \"codeclimate-test-reporter < coverage/lcov.info\"",
        "cover:test": "nyc --reporter=lcov --reporter=text npm test",
        "lint": "eslint src test",
        "mocha": "mocha spec/index.js",
        "postversion": "node changelog.js > CHANGELOG.md && git add CHANGELOG.md && echo ':wq' | git commit --amend && git push --follow-tags",
        "start": "abby compile, watch:*",
        "test": "abby compile, mocha.",
        "watch:copy": "abby compile:copy --watch test/spec.js",
        "watch:mocha": "abby mocha --log --watch lib/**/*.js,spec/**/*.js",
        "watch:src": "babel src --out-dir lib --watch",
        "watch:test": "babel test --out-dir spec --ignore test/spec.js --watch"
    },
    "version": "0.2.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
