# test coverage for  [flux (v3.1.2)](http://facebook.github.io/flux/)  [![npm package](https://img.shields.io/npm/v/npmtest-flux.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-flux) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-flux.svg)](https://travis-ci.org/npmtest/node-npmtest-flux)
#### An application architecture based on a unidirectional data flow

[![NPM](https://nodei.co/npm/flux.png?downloads=true)](https://www.npmjs.com/package/flux)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-flux/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-flux/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-flux/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-flux/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-flux/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-flux/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-flux/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-flux/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-flux/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-flux/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-flux%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-flux/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-flux/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-flux%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-flux/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-flux/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-flux/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Facebook"
    },
    "bugs": {
        "url": "https://github.com/facebook/flux/issues"
    },
    "contributors": [
        {
            "name": "Jing Chen",
            "email": "jingc@fb.com"
        },
        {
            "name": "Bill Fisher",
            "email": "fisherwebdev@gmail.com"
        },
        {
            "name": "Paul O'Shannessy",
            "email": "paul@oshannessy.com"
        },
        {
            "name": "Kyle Davis",
            "email": "kyldvs@gmail.com"
        }
    ],
    "dependencies": {
        "fbemitter": "^2.0.0",
        "fbjs": "^0.8.0"
    },
    "description": "An application architecture based on a unidirectional data flow",
    "devDependencies": {
        "babel-core": "^5.8.22",
        "babel-loader": "^5.3.2",
        "del": "^2.2.0",
        "fbjs-scripts": "^0.5.0",
        "gulp": "^3.9.0",
        "gulp-babel": "^5.1.0",
        "gulp-flatten": "^0.2.0",
        "gulp-header": "1.8.2",
        "gulp-rename": "^1.2.2",
        "gulp-util": "^3.0.6",
        "immutable": "^3.7.4",
        "jest": "^15.1.1",
        "object-assign": "^4.0.1",
        "react": "^15.0.2",
        "react-addons-test-utils": "^15.0.1",
        "react-dom": "^15.0.1",
        "run-sequence": "^1.1.0",
        "vinyl-source-stream": "^1.0.0",
        "webpack": "^1.11.0",
        "webpack-stream": "^3.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8c170addf95b8cb2febb3ddd640aa3e24505762f",
        "tarball": "https://registry.npmjs.org/flux/-/flux-3.1.2.tgz"
    },
    "files": [
        "LICENSE",
        "PATENTS",
        "README.md",
        "index.js",
        "lib",
        "utils.js",
        "dist"
    ],
    "gitHead": "a6dfedde64ea4c8190da8ddcf4486f28ca39a2d3",
    "homepage": "http://facebook.github.io/flux/",
    "jest": {
        "modulePathIgnorePatterns": [
            "/lib/",
            "/node_modules/"
        ],
        "preprocessorIgnorePatterns": [
            "/node_modules/"
        ],
        "rootDir": "./",
        "scriptPreprocessor": "scripts/jest/preprocessor.js",
        "setupFiles": [
            "scripts/jest/environment.js"
        ],
        "testPathDirs": [
            "<rootDir>/src"
        ]
    },
    "keywords": [
        "flux",
        "react",
        "facebook",
        "dispatcher"
    ],
    "license": "BSD-3-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "fisherwebdev",
            "email": "fisherwebdev@gmail.com"
        },
        {
            "name": "fb",
            "email": "opensource+npm@fb.com"
        },
        {
            "name": "kyldvs",
            "email": "kyldvs@gmail.com"
        }
    ],
    "name": "flux",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15.0.2"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/facebook/flux.git"
    },
    "scripts": {
        "build": "gulp build",
        "prepublish": "gulp publish",
        "test": "NODE_ENV=test jest"
    },
    "version": "3.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
