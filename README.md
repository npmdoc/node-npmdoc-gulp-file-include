# npmdoc-gulp-file-include

#### api documentation for  [gulp-file-include (v1.1.0)](https://github.com/coderhaoxin/gulp-file-include#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-file-include.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-file-include) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-file-include.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-file-include)

#### a gulp plugin for file include

[![NPM](https://nodei.co/npm/gulp-file-include.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-file-include)

- [https://npmdoc.github.io/node-npmdoc-gulp-file-include/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-file-include/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-file-include/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-file-include/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-file-include/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-file-include/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "haoxin"
    },
    "bugs": {
        "url": "https://github.com/coderhaoxin/gulp-file-include/issues"
    },
    "contributors": [
        {
            "name": "Bogdan Chadkin"
        },
        {
            "name": "Arthur Araújo"
        }
    ],
    "dependencies": {
        "balanced-match": "^0.4.2",
        "concat-stream": "^1.6.0",
        "extend": "^3.0.0",
        "flatnest": "^1.0.0",
        "gulp-util": "^3.0.8",
        "through2": "^2.0.3"
    },
    "description": "a gulp plugin for file include",
    "devDependencies": {
        "gulp": "3",
        "istanbul": "0",
        "markdown": "0",
        "mocha": "3",
        "should": "11"
    },
    "directories": {},
    "dist": {
        "shasum": "2c7204332020d56fe29107e81914e4a923f2826d",
        "tarball": "https://registry.npmjs.org/gulp-file-include/-/gulp-file-include-1.1.0.tgz"
    },
    "files": [
        "lib"
    ],
    "gitHead": "08ca0930d40ffdf0aea77fbc1b9e84e69fd34bf0",
    "homepage": "https://github.com/coderhaoxin/gulp-file-include#readme",
    "keywords": [
        "gulpplugin",
        "file",
        "include",
        "replace",
        "gulp",
        "plugin"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "coderhaoxin"
        },
        {
            "name": "trysound"
        },
        {
            "name": "haoxins"
        }
    ],
    "name": "gulp-file-include",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/coderhaoxin/gulp-file-include.git"
    },
    "scripts": {
        "jscs": "jscs lib && jscs test",
        "test": "mocha -R spec -t 200 test/*.js",
        "test-cov": "istanbul cover node_modules/.bin/_mocha -- -R dot -t 200 test/*.js",
        "test-travis": "istanbul cover node_modules/.bin/_mocha --report lcovonly -- -R dot -t 200 test/*.js"
    },
    "version": "1.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
