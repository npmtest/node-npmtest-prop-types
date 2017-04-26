# npmtest-prop-types

#### basic test coverage for  [prop-types (v15.5.8)](https://facebook.github.io/react/)  [![npm package](https://img.shields.io/npm/v/npmtest-prop-types.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-prop-types) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-prop-types.svg)](https://travis-ci.org/npmtest/node-npmtest-prop-types)

#### Runtime type checking for React props and similar objects.

[![NPM](https://nodei.co/npm/prop-types.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/prop-types)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-prop-types/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-prop-types/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-prop-types/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-prop-types/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-prop-types/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-prop-types/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-prop-types/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-prop-types/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-prop-types/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-prop-types/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-prop-types/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-prop-types/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-prop-types/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-prop-types/build/test-report.html](https://npmtest.github.io/node-npmtest-prop-types/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-prop-types/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-prop-types/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-prop-types/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-prop-types/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-prop-types/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-prop-types/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-prop-types/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-prop-types/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/reactjs/prop-types/issues"
    },
    "dependencies": {
        "fbjs": "^0.8.9"
    },
    "description": "Runtime type checking for React props and similar objects.",
    "devDependencies": {
        "babel-jest": "^19.0.0",
        "babel-preset-react": "^6.24.1",
        "browserify": "^14.3.0",
        "bundle-collapser": "^1.2.1",
        "envify": "^4.0.0",
        "jest": "^19.0.2",
        "react": "^15.5.1",
        "uglifyify": "^3.0.4",
        "uglifyjs": "^2.4.10"
    },
    "directories": {},
    "dist": {
        "shasum": "6b7b2e141083be38c8595aa51fc55775c7199394",
        "tarball": "https://registry.npmjs.org/prop-types/-/prop-types-15.5.8.tgz"
    },
    "files": [
        "LICENSE",
        "PATENTS",
        "README.md",
        "checkPropTypes.js",
        "factory.js",
        "factoryWithThrowingShims.js",
        "factoryWithTypeCheckers.js",
        "index.js",
        "prop-types.js",
        "prop-types.min.js",
        "lib"
    ],
    "gitHead": "49536324c3d5cf2331aa7e5fa832db3d84abd5cd",
    "homepage": "https://facebook.github.io/react/",
    "keywords": [
        "react"
    ],
    "license": "BSD-3-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "acdlite"
        },
        {
            "name": "brianvaughn"
        },
        {
            "name": "flarnie"
        },
        {
            "name": "gaearon"
        },
        {
            "name": "sebmarkbage"
        },
        {
            "name": "spicyj"
        },
        {
            "name": "theron"
        },
        {
            "name": "tomocchino"
        },
        {
            "name": "trueadm"
        }
    ],
    "name": "prop-types",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/reactjs/prop-types.git"
    },
    "scripts": {
        "build": "yarn umd && yarn umd-min",
        "prepublish": "yarn build",
        "test": "jest",
        "umd": "NODE_ENV=development browserify index.js -t envify --standalone PropTypes -o prop-types.js",
        "umd-min": "NODE_ENV=production browserify index.js -t envify -t uglifyify --standalone PropTypes  -p bundle-collapser/plugin -o | uglifyjs --compress unused,dead_code -o prop-types.min.js"
    },
    "version": "15.5.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
