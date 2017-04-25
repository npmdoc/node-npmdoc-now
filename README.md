# npmdoc-now

#### basic api documentation for  [now (v4.11.2)](https://github.com/zeit/now-cli#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-now.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-now) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-now.svg)](https://travis-ci.org/npmdoc/node-npmdoc-now)

#### The command line interface for Now

[![NPM](https://nodei.co/npm/now.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/now)

- [https://npmdoc.github.io/node-npmdoc-now/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-now/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-now/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-now/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-now/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-now/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "ava": {
        "failFast": true,
        "files": [
            "test/*.js"
        ]
    },
    "bin": {
        "now": "./build/bin/now.js"
    },
    "bugs": {
        "url": "https://github.com/zeit/now-cli/issues"
    },
    "dependencies": {
        "@google/maps": "0.3.1",
        "ansi-escapes": "1.4.0",
        "ansi-regex": "2.1.1",
        "arr-flatten": "1.0.2",
        "array-unique": "0.3.2",
        "async-retry": "0.3.0",
        "async-to-gen": "1.3.2",
        "bytes": "2.5.0",
        "chalk": "1.1.3",
        "copy-paste": "1.3.0",
        "credit-card": "3.0.1",
        "cross-spawn": "5.1.0",
        "docker-file-parser": "1.0.1",
        "dotenv": "4.0.0",
        "download": "5.0.3",
        "email-prompt": "0.2.0",
        "email-validator": "1.0.7",
        "fs-promise": "2.0.2",
        "glob": "7.1.1",
        "ignore": "3.2.7",
        "ini": "1.3.4",
        "inquirer": "3.0.6",
        "is-url": "1.2.2",
        "minimist": "1.2.0",
        "ms": "1.0.0",
        "node-fetch": "1.6.3",
        "node-version": "1.0.0",
        "opn": "4.0.2",
        "ora": "1.2.0",
        "progress": "2.0.0",
        "psl": "1.1.18",
        "resumer": "0.0.0",
        "socket.io-client": "1.7.3",
        "split-array": "1.0.1",
        "strip-ansi": "3.0.1",
        "stripe": "4.17.1",
        "text-table": "0.2.0",
        "tmp-promise": "1.0.3",
        "update-notifier": "2.1.0"
    },
    "description": "The command line interface for Now",
    "devDependencies": {
        "alpha-sort": "2.0.1",
        "ava": "0.19.1",
        "eslint-config-prettier": "1.6.0",
        "husky": "0.13.3",
        "lint-staged": "3.4.0",
        "pkg": "3.0.0-beta.29",
        "prettier": "1.1.0",
        "slackup": "2.0.1",
        "xo": "0.18.1"
    },
    "directories": {},
    "dist": {
        "shasum": "a27c4b23aa0a2aed792b01664176bb7717b1c606",
        "tarball": "https://registry.npmjs.org/now/-/now-4.11.2.tgz"
    },
    "engines": {
        "node": ">=6.9.0"
    },
    "files": [
        "build"
    ],
    "gitHead": "20552717321a5f5cf848e1268583159d53b5b74f",
    "homepage": "https://github.com/zeit/now-cli#readme",
    "license": "MIT",
    "lint-staged": {
        "*.js": [
            "npm run lint",
            "prettier --single-quote --write",
            "git add"
        ]
    },
    "maintainers": [
        {
            "name": "jamo"
        },
        {
            "name": "leo"
        },
        {
            "name": "matheuss"
        },
        {
            "name": "rase-"
        },
        {
            "name": "rauchg"
        }
    ],
    "name": "now",
    "optionalDependencies": {},
    "pkg": {
        "scripts": [
            "bin/*",
            "lib/**/*"
        ]
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zeit/now-cli.git"
    },
    "scripts": {
        "build": "./build.sh",
        "lint": "xo",
        "pack": "pkg bin/now.js --config package.json --out-dir packed -t node7-alpine-x64,node7-linux-x64,node7-macos-x64,node7-win-x64",
        "precommit": "lint-staged",
        "prepublish": "npm run build",
        "test": "npm run build && npm run lint && ava"
    },
    "version": "4.11.2",
    "xo": {
        "ignores": [
            "test/_fixtures/**",
            "scripts/build/**"
        ],
        "extends": "prettier"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
