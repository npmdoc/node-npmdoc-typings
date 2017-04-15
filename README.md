# api documentation for  [typings (v2.1.1)](https://github.com/typings/typings)  [![npm package](https://img.shields.io/npm/v/npmdoc-typings.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-typings) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-typings.svg)](https://travis-ci.org/npmdoc/node-npmdoc-typings)
#### The TypeScript Definition Manager

[![NPM](https://nodei.co/npm/typings.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/typings)

[![apidoc](https://npmdoc.github.io/node-npmdoc-typings/build/screenCapture.buildCi.browser.apidoc.html.png)](https://npmdoc.github.io/node-npmdoc-typings/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-typings/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-typings/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Blake Embrey",
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
        "cli-truncate": "^1.0.0",
        "columnify": "^1.5.2",
        "elegant-spinner": "^1.0.1",
        "has-unicode": "^2.0.1",
        "listify": "^1.0.0",
        "log-update": "^1.0.2",
        "minimist": "^1.2.0",
        "promise-finally": "^3.0.0",
        "typings-core": "^2.3.3",
        "update-notifier": "^2.0.0",
        "wordwrap": "^1.0.0",
        "xtend": "^4.0.1"
    },
    "description": "The TypeScript Definition Manager",
    "devDependencies": {
        "dependency-check": "^2.5.1",
        "nock": "^9.0.0",
        "rimraf": "^2.5.2",
        "ts-node": "^3.0.0",
        "tslint": "^5.0.0",
        "tslint-config-standard": "^5.0.0",
        "typescript": "^2.1.4"
    },
    "directories": {},
    "dist": {
        "shasum": "bacc69d255970a478e09f76c7f689975d535a78a",
        "tarball": "https://registry.npmjs.org/typings/-/typings-2.1.1.tgz"
    },
    "files": [
        "dist/",
        "typings.json"
    ],
    "gitHead": "ce773a3f6ac37fd48d7acc498ed54232bd5ef6ca",
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
            "name": "blakeembrey"
        }
    ],
    "name": "typings",
    "optionalDependencies": {},
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
    "version": "2.1.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module typings](#apidoc.module.typings)



# <a name="apidoc.module.typings"></a>[module typings](#apidoc.module.typings)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
