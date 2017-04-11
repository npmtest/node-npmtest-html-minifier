# test coverage for  [html-minifier (v3.4.3)](http://kangax.github.io/html-minifier/)  [![npm package](https://img.shields.io/npm/v/npmtest-html-minifier.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-html-minifier) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-html-minifier.svg)](https://travis-ci.org/npmtest/node-npmtest-html-minifier)
#### Highly configurable, well-tested, JavaScript-based HTML minifier.

[![NPM](https://nodei.co/npm/html-minifier.png?downloads=true)](https://www.npmjs.com/package/html-minifier)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-html-minifier/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-html-minifier/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-html-minifier/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-html-minifier/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-html-minifier/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-html-minifier/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-html-minifier/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-html-minifier/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-html-minifier/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-html-minifier/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-html-minifier%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-html-minifier/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-html-minifier/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-html-minifier%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-html-minifier/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-html-minifier/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-html-minifier/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Juriy \"kangax\" Zaytsev"
    },
    "benchmarkDependencies": {
        "brotli": "1.3.x",
        "chalk": "1.1.x",
        "cli-table": "0.3.x",
        "lzma": "2.3.x",
        "minimize": "2.1.x",
        "progress": "2.0.x"
    },
    "bin": {
        "html-minifier": "./cli.js"
    },
    "bugs": {
        "url": "https://github.com/kangax/html-minifier/issues"
    },
    "contributors": [
        {
            "name": "Gilmore Davidson",
            "url": "https://github.com/gilmoreorless"
        },
        {
            "name": "Hugo Wetterberg",
            "email": "hugo@wetterberg.nu"
        },
        {
            "name": "Zoltan Frombach",
            "email": "tssajo@gmail.com"
        }
    ],
    "dependencies": {
        "camel-case": "3.0.x",
        "clean-css": "4.0.x",
        "commander": "2.9.x",
        "he": "1.1.x",
        "ncname": "1.0.x",
        "param-case": "2.1.x",
        "relateurl": "0.2.x",
        "uglify-js": "~2.8.22"
    },
    "description": "Highly configurable, well-tested, JavaScript-based HTML minifier.",
    "devDependencies": {
        "grunt": "1.0.x",
        "grunt-browserify": "5.0.x",
        "grunt-contrib-uglify": "2.3.x",
        "gruntify-eslint": "3.1.x",
        "phantomjs-prebuilt": "2.1.x",
        "qunitjs": "2.x",
        "uglify-to-browserify": "1.0.x"
    },
    "directories": {},
    "dist": {
        "shasum": "eb3a7297c804611f470454eeebe0aacc427e424a",
        "tarball": "https://registry.npmjs.org/html-minifier/-/html-minifier-3.4.3.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "src/*.js",
        "cli.js",
        "sample-cli-config-file.conf"
    ],
    "gitHead": "afaafeb2b3aa9f1a1b9a9c54275092a8202b9a28",
    "homepage": "http://kangax.github.io/html-minifier/",
    "keywords": [
        "cli",
        "compress",
        "compressor",
        "css",
        "html",
        "htmlmin",
        "javascript",
        "min",
        "minification",
        "minifier",
        "minify",
        "optimize",
        "optimizer",
        "pack",
        "packer",
        "parse",
        "parser",
        "uglifier",
        "uglify"
    ],
    "license": "MIT",
    "main": "src/htmlminifier.js",
    "maintainers": [
        {
            "name": "alexlamsl",
            "email": "alex+npm@starthq.com"
        },
        {
            "name": "kangax",
            "email": "kangax@gmail.com"
        }
    ],
    "name": "html-minifier",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kangax/html-minifier.git"
    },
    "scripts": {
        "dist": "grunt dist",
        "test": "grunt test"
    },
    "version": "3.4.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
