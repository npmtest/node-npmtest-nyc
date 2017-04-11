# test coverage for  [nyc (v10.2.0)](https://github.com/istanbuljs/nyc#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-nyc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nyc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nyc.svg)](https://travis-ci.org/npmtest/node-npmtest-nyc)
#### the Istanbul command line interface

[![NPM](https://nodei.co/npm/nyc.png?downloads=true)](https://www.npmjs.com/package/nyc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nyc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nyc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nyc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nyc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nyc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nyc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nyc/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nyc/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-nyc/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-nyc/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-nyc%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nyc/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nyc/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-nyc%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nyc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nyc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nyc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Coe",
        "email": "ben@npmjs.com"
    },
    "bin": {
        "nyc": "./bin/nyc.js"
    },
    "bugs": {
        "url": "https://github.com/istanbuljs/nyc/issues"
    },
    "bundleDependencies": [
        "archy",
        "arrify",
        "caching-transform",
        "convert-source-map",
        "debug-log",
        "default-require-extensions",
        "find-cache-dir",
        "find-up",
        "foreground-child",
        "glob",
        "istanbul-lib-coverage",
        "istanbul-lib-hook",
        "istanbul-lib-instrument",
        "istanbul-lib-report",
        "istanbul-lib-source-maps",
        "istanbul-reports",
        "md5-hex",
        "merge-source-map",
        "micromatch",
        "mkdirp",
        "resolve-from",
        "rimraf",
        "signal-exit",
        "spawn-wrap",
        "test-exclude",
        "yargs",
        "yargs-parser"
    ],
    "contributors": [
        {
            "name": "Isaac Schlueter"
        },
        {
            "name": "Mark Wubben"
        },
        {
            "name": "James Talmage"
        },
        {
            "name": "Krishnan Anantheswaran"
        }
    ],
    "dependencies": {
        "archy": "^1.0.0",
        "arrify": "^1.0.1",
        "caching-transform": "^1.0.0",
        "convert-source-map": "^1.3.0",
        "debug-log": "^1.0.1",
        "default-require-extensions": "^1.0.0",
        "find-cache-dir": "^0.1.1",
        "find-up": "^1.1.2",
        "foreground-child": "^1.5.3",
        "glob": "^7.0.6",
        "istanbul-lib-coverage": "^1.0.2",
        "istanbul-lib-hook": "^1.0.5",
        "istanbul-lib-instrument": "^1.7.0",
        "istanbul-lib-report": "^1.0.0",
        "istanbul-lib-source-maps": "^1.1.1",
        "istanbul-reports": "^1.0.2",
        "md5-hex": "^1.2.0",
        "merge-source-map": "^1.0.2",
        "micromatch": "^2.3.11",
        "mkdirp": "^0.5.0",
        "resolve-from": "^2.0.0",
        "rimraf": "^2.5.4",
        "signal-exit": "^3.0.1",
        "spawn-wrap": "1.2.4",
        "test-exclude": "^4.0.0",
        "yargs": "^7.0.2",
        "yargs-parser": "^4.0.2"
    },
    "description": "the Istanbul command line interface",
    "devDependencies": {
        "any-path": "^1.3.0",
        "bundle-dependencies": "^1.0.2",
        "chai": "^3.0.0",
        "coveralls": "^2.11.11",
        "exists-sync": "0.0.4",
        "forking-tap": "^0.1.1",
        "is-windows": "^1.0.0",
        "lodash": "^4.12.0",
        "newline-regex": "^0.2.1",
        "requirejs": "^2.3.0",
        "sanitize-filename": "^1.5.3",
        "sinon": "^2.1.0",
        "source-map-support": "^0.4.6",
        "split-lines": "^1.0.0",
        "standard": "^9.0.2",
        "standard-version": "^4.0.0",
        "tap": "^10.0.0",
        "which": "^1.2.11",
        "zero-fill": "^2.2.3"
    },
    "directories": {},
    "dist": {
        "shasum": "facd90240600c9aa4dd81ea99c2fb6a85c53de0c",
        "tarball": "https://registry.npmjs.org/nyc/-/nyc-10.2.0.tgz"
    },
    "files": [
        "index.js",
        "bin/*.js",
        "lib/*.js",
        "lib/commands/*.js",
        "lib/instrumenters/*.js",
        "!**/*covered.js"
    ],
    "gitHead": "455619f9fdd0a1f4fa08b0621e030cceda969011",
    "greenkeeper": {
        "ignore": [
            "find-up"
        ]
    },
    "homepage": "https://github.com/istanbuljs/nyc#readme",
    "keywords": [
        "coverage",
        "reporter",
        "subprocess",
        "testing"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bcoe",
            "email": "ben@npmjs.com"
        },
        {
            "name": "isaacs",
            "email": "isaacs@npmjs.com"
        }
    ],
    "name": "nyc",
    "nyc": {
        "exclude": [
            "node_modules",
            "bin",
            "coverage",
            "test/fixtures/coverage.js",
            "test/build/*",
            "test/nyc-test.js",
            "index.covered.js",
            "test/fixtures/_generateCoverage.js"
        ]
    },
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/istanbuljs/nyc.git"
    },
    "scripts": {
        "build": "node ./build-tests",
        "bundle": "bundle-dependencies update",
        "clean": "rimraf ./.nyc_output ./node_modules/.cache ./.self_coverage ./test/fixtures/.nyc_output ./test/fixtures/node_modules/.cache *covered.js ./lib/*covered.js",
        "cover": "npm run clean && npm run build && npm run instrument && npm run run-tests && npm run report",
        "dev": "npm run clean && npm run build && npm run run-tests",
        "instrument": "node ./build-self-coverage.js",
        "pretest": "standard",
        "release": "standard-version",
        "report": "node ./bin/nyc  --temp-directory ./.self_coverage/ -r text -r lcov report",
        "run-tests": "tap -t120 --no-cov -b ./test/build/*.js ./test/src/nyc-bin.js ./test/src/process-args.js",
        "test": "npm run cover"
    },
    "standard": {
        "ignore": [
            "**/fixtures/**",
            "**/test/build/*"
        ]
    },
    "version": "10.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
