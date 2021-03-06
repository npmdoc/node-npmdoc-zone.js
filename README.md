# npmdoc-zone.js

#### basic api documentation for  [zone.js (v0.8.8)](https://github.com/angular/zone.js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-zone.js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-zone.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-zone.js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-zone.js)

#### Zones for JavaScript

[![NPM](https://nodei.co/npm/zone.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/zone.js)

- [https://npmdoc.github.io/node-npmdoc-zone.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-zone.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-zone.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-zone.js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-zone.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-zone.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brian Ford"
    },
    "browser": "dist/zone.js",
    "bugs": {
        "url": "https://github.com/angular/zone.js/issues"
    },
    "dependencies": {},
    "description": "Zones for JavaScript",
    "devDependencies": {
        "@types/jasmine": "2.2.33",
        "@types/node": "^6.0.38",
        "@types/systemjs": "^0.19.30",
        "clang-format": "1.0.46",
        "concurrently": "^2.2.0",
        "conventional-changelog": "^1.1.0",
        "es6-promise": "^3.0.2",
        "google-closure-compiler": "^20170409.0.0",
        "gulp": "^3.8.11",
        "gulp-clang-format": "^1.0.23",
        "gulp-conventional-changelog": "^1.1.0",
        "gulp-rename": "^1.2.2",
        "gulp-rollup": "^2.3.0",
        "gulp-tsc": "^1.1.4",
        "gulp-tslint": "^7.0.1",
        "gulp-uglify": "^1.2.0",
        "gulp-util": "^3.0.7",
        "jasmine": "^2.4.1",
        "jasmine-core": "^2.2.0",
        "karma": "^0.13.14",
        "karma-chrome-launcher": "^0.2.1",
        "karma-firefox-launcher": "^0.1.4",
        "karma-jasmine": "^0.3.6",
        "karma-mocha": "^1.2.0",
        "karma-safari-launcher": "^0.1.1",
        "karma-sauce-launcher": "^0.2.10",
        "karma-sourcemap-loader": "^0.3.6",
        "mocha": "^3.1.2",
        "nodejs-websocket": "^1.2.0",
        "promises-aplus-tests": "^2.1.2",
        "pump": "^1.0.1",
        "systemjs": "^0.19.37",
        "ts-loader": "^0.6.0",
        "tslint": "^4.1.1",
        "tslint-eslint-rules": "^3.1.0",
        "typescript": "2.2.1",
        "vrsource-tslint-rules": "^4.0.0",
        "whatwg-fetch": "^2.0.1"
    },
    "directories": {
        "lib": "lib",
        "test": "test"
    },
    "dist": {
        "shasum": "354f02bb7241af834bb83b310308a89ad012d3af",
        "tarball": "https://registry.npmjs.org/zone.js/-/zone.js-0.8.8.tgz"
    },
    "files": [
        "lib",
        "dist"
    ],
    "gitHead": "7b43b51239d21753f50df04eff3dac6f89e5328c",
    "homepage": "https://github.com/angular/zone.js#readme",
    "license": "MIT",
    "main": "dist/zone-node.js",
    "maintainers": [
        {
            "name": "angular"
        },
        {
            "name": "angularcore"
        },
        {
            "name": "btford"
        }
    ],
    "name": "zone.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/angular/zone.js.git"
    },
    "scripts": {
        "changelog": "gulp changelog",
        "ci": "npm run lint && npm run format && npm run promisetest && npm run test:single && npm run test-node",
        "closure:test": "scripts/closure/closure_compiler.sh",
        "format": "gulp format:enforce",
        "karma-jasmine": "karma start karma-build-jasmine.conf.js",
        "karma-jasmine:autoclose": "npm run karma-jasmine:single && npm run ws-client",
        "karma-jasmine:single": "karma start karma-build-jasmine.conf.js --single-run",
        "lint": "gulp lint",
        "prepublish": "tsc && gulp build",
        "promisetest": "gulp promisetest",
        "serve": "python -m SimpleHTTPServer 8000",
        "test": "npm run tsc && concurrently \"npm run tsc:w\" \"npm run ws-server\" \"npm run karma-jasmine\"",
        "test-dist": "concurrently \"npm run tsc:w\" \"npm run ws-server\" \"karma start karma-dist-jasmine.conf.js\"",
        "test-mocha": "npm run tsc && concurrently \"npm run tsc:w\" \"npm run ws-server\" \"karma start karma-build-mocha.conf.js\"",
        "test-node": "gulp test/node",
        "test:single": "npm run tsc && concurrently \"npm run ws-server\" \"npm run karma-jasmine:autoclose\"",
        "tsc": "tsc",
        "tsc:w": "tsc -w",
        "ws-client": "node ./test/ws-client.js",
        "ws-server": "node ./test/ws-server.js"
    },
    "typings": "dist/zone.js.d.ts",
    "version": "0.8.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
