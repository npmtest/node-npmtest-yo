# npmtest-yo

#### basic test coverage for  [yo (v1.8.5)](http://yeoman.io)  [![npm package](https://img.shields.io/npm/v/npmtest-yo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-yo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-yo.svg)](https://travis-ci.org/npmtest/node-npmtest-yo)

#### CLI tool for running Yeoman generators

[![NPM](https://nodei.co/npm/yo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-yo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-yo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-yo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-yo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-yo/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-yo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-yo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-yo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-yo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-yo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-yo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-yo/build/test-report.html](https://npmtest.github.io/node-npmtest-yo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-yo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-yo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-yo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-yo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-yo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "yo",
    "version": "1.8.5",
    "description": "CLI tool for running Yeoman generators",
    "homepage": "http://yeoman.io",
    "author": "Yeoman",
    "files": [
        "lib"
    ],
    "main": "lib",
    "keywords": [
        "cli-app",
        "cli",
        "front-end",
        "development",
        "dev",
        "build",
        "web",
        "tool",
        "scaffold",
        "stack",
        "yeoman",
        "generator",
        "generate",
        "app",
        "boilerplate"
    ],
    "license": "BSD-2-Clause",
    "repository": "yeoman/yo",
    "bin": {
        "yo": "lib/cli.js",
        "yo-complete": "lib/completion/index.js"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "scripts": {
        "test": "gulp",
        "postinstall": "yodoctor",
        "postupdate": "yodoctor",
        "prepublish": "gulp prepublish"
    },
    "dependencies": {
        "async": "^1.0.0",
        "chalk": "^1.0.0",
        "cli-list": "^0.1.1",
        "configstore": "^1.0.0",
        "cross-spawn": "^3.0.1",
        "figures": "^1.3.5",
        "fullname": "^2.0.0",
        "got": "^5.0.0",
        "humanize-string": "^1.0.0",
        "inquirer": "^0.11.0",
        "insight": "^0.7.0",
        "lodash": "^3.2.0",
        "meow": "^3.0.0",
        "npm-keyword": "^4.1.0",
        "opn": "^3.0.2",
        "package-json": "^2.1.0",
        "parse-help": "^0.1.1",
        "read-pkg-up": "^1.0.1",
        "repeating": "^2.0.0",
        "root-check": "^1.0.0",
        "sort-on": "^1.0.0",
        "string-length": "^1.0.0",
        "tabtab": "^1.3.0",
        "titleize": "^1.0.0",
        "update-notifier": "^0.6.0",
        "user-home": "^2.0.0",
        "yeoman-character": "^1.0.0",
        "yeoman-doctor": "^2.0.0",
        "yeoman-environment": "^1.6.1",
        "yosay": "^1.0.0"
    },
    "devDependencies": {
        "gulp": "^3.6.0",
        "gulp-coveralls": "^0.1.0",
        "gulp-eslint": "^2.0.0",
        "gulp-exclude-gitignore": "^1.0.0",
        "gulp-istanbul": "^0.10.4",
        "gulp-mocha": "^2.0.0",
        "gulp-nsp": "^2.1.0",
        "gulp-plumber": "^1.0.0",
        "mocha": "^2.1.0",
        "mockery": "^1.4.0",
        "nock": "^8.0.0",
        "nsp": "^2.2.0",
        "proxyquire": "^1.0.1",
        "registry-url": "^3.0.0",
        "sinon": "^1.12.1"
    },
    "tabtab": {
        "yo": [
            "-f",
            "--force",
            "--version",
            "--no-color",
            "--no-insight",
            "--insight",
            "--generators"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
