# npmtest-s3

#### test coverage for  [s3 (v4.4.0)](https://github.com/andrewrk/node-s3-client)  [![npm package](https://img.shields.io/npm/v/npmtest-s3.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-s3) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-s3.svg)](https://travis-ci.org/npmtest/node-npmtest-s3)

#### high level amazon s3 client. upload and download files and directories

[![NPM](https://nodei.co/npm/s3.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/s3)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-s3/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-s3/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-s3/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-s3/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-s3/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-s3/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-s3/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-s3/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-s3/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-s3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-s3/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-s3/build/test-report.html](https://npmtest.github.io/node-npmtest-s3/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-s3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-s3/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-s3/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-s3/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-s3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-s3/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-s3/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-s3/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrew Kelley"
    },
    "bugs": {
        "url": "https://github.com/andrewrk/node-s3-client/issues"
    },
    "dependencies": {
        "aws-sdk": "~2.0.31",
        "fd-slicer": "~1.0.0",
        "findit2": "~2.2.3",
        "graceful-fs": "~3.0.5",
        "mime": "~1.2.11",
        "mkdirp": "~0.5.0",
        "pend": "~1.2.0",
        "rimraf": "~2.2.8",
        "streamsink": "~1.2.0"
    },
    "description": "high level amazon s3 client. upload and download files and directories",
    "devDependencies": {
        "mocha": "~2.0.1",
        "ncp": "~1.0.1"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "56a4f775515a7b6b9c8e5c6b1ab51f9037669f1f",
        "tarball": "https://registry.npmjs.org/s3/-/s3-4.4.0.tgz"
    },
    "engines": {
        "node": ">=0.10.20"
    },
    "gitHead": "8e9cd927cb40c121256c46bd321998bd2aa804d0",
    "homepage": "https://github.com/andrewrk/node-s3-client",
    "keywords": [
        "amazon",
        "s3",
        "sync",
        "folder",
        "directory",
        "retry",
        "limit",
        "stream",
        "async",
        "parallel",
        "multipart",
        "size"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "superjoe"
        }
    ],
    "name": "s3",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/andrewrk/node-s3-client.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "4.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
