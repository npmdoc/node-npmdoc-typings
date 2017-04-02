# api documentation for  [typings (v2.1.0)](https://github.com/typings/typings)  [![npm package](https://img.shields.io/npm/v/npmdoc-typings.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-typings) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-typings.svg)](https://travis-ci.org/npmdoc/node-npmdoc-typings)
#### The TypeScript Definition Manager

[![NPM](https://nodei.co/npm/typings.png?downloads=true)](https://www.npmjs.com/package/typings)

[![apidoc](https://npmdoc.github.io/node-npmdoc-typings/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-typings_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-typings/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-typings/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Blake Embrey",
        "email": "hello@blakeembrey.com",
        "url": "http://blakeembrey.me"
    },
    "bin": {
        "typings": "dist/bin.js"
    },
    "bugs": {
        "url": "https://github.com/typings/typings/issues"
    },
    "dependencies": {
        "archy": "^1.0.0",
        "bluebird": "^3.1.1",
        "chalk": "^1.0.0",
        "cli-truncate": "^0.2.1",
        "columnify": "^1.5.2",
        "elegant-spinner": "^1.0.1",
        "has-unicode": "^2.0.1",
        "listify": "^1.0.0",
        "log-update": "^1.0.2",
        "minimist": "^1.2.0",
        "promise-finally": "^3.0.0",
        "typings-core": "^2.2.0",
        "update-notifier": "^1.0.0",
        "wordwrap": "^1.0.0",
        "xtend": "^4.0.1"
    },
    "description": "The TypeScript Definition Manager",
    "devDependencies": {
        "dependency-check": "^2.5.1",
        "nock": "^9.0.0",
        "rimraf": "^2.5.2",
        "ts-node": "^1.0.0",
        "tslint": "^4.0.2",
        "tslint-config-standard": "^2.0.0",
        "typescript": "^2.1.4"
    },
    "directories": {},
    "dist": {
        "shasum": "9cdbe0cd1626ab61b379e06ba4a3910d1d791006",
        "tarball": "https://registry.npmjs.org/typings/-/typings-2.1.0.tgz"
    },
    "files": [
        "dist/",
        "typings.json"
    ],
    "gitHead": "afc99a2e285fd2331dd06bf5d81e51821fa11426",
    "homepage": "https://github.com/typings/typings",
    "keywords": [
        "typings",
        "typescript",
        "definition",
        "declaration",
        "package",
        "manager",
        "typed"
    ],
    "license": "MIT",
    "main": "dist/bin.js",
    "maintainers": [
        {
            "name": "blakeembrey",
            "email": "hello@blakeembrey.com"
        }
    ],
    "name": "typings",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/typings/typings.git"
    },
    "scripts": {
        "build": "rimraf dist/ && tsc",
        "dependency-check": "dependency-check . --entry dist/bin.js --missing --no-dev && dependency-check . --entry dist/bin.js --unused --no-dev -i bluebird",
        "docs": "node scripts/docs-commands.js",
        "lint": "tslint 'src/**/*.ts'",
        "prepublish": "node -e \"require('typings-core').install({ cwd: process.cwd() })\" && npm run build",
        "test": "npm run lint && npm run build && npm run dependency-check"
    },
    "version": "2.1.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module typings](#apidoc.module.typings)



# <a name="apidoc.module.typings"></a>[module typings](#apidoc.module.typings)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
