# npmdoc-generator-ng-fullstack

#### api documentation for  generator-ng-fullstack (v1.9.14)  [![npm package](https://img.shields.io/npm/v/npmdoc-generator-ng-fullstack.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-generator-ng-fullstack) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-generator-ng-fullstack.svg)](https://travis-ci.org/npmdoc/node-npmdoc-generator-ng-fullstack)

#### Client, server or fullstack - it's up to you. ng-fullstack gives you the best of the latest: Node, Go, HTTP/2, Angular 1, Angular 2, Vue, Aurelia, Express, Koa, Echo, Gin, MongoDB, Gulp, Babel, Typescript and much more.

[![NPM](https://nodei.co/npm/generator-ng-fullstack.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-ng-fullstack)

- [https://npmdoc.github.io/node-npmdoc-generator-ng-fullstack/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-ng-fullstack/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-ng-fullstack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-ng-fullstack/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-generator-ng-fullstack/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-generator-ng-fullstack/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "generator-ng-fullstack",
    "version": "1.9.14",
    "description": "Client, server or fullstack - it's up to you. ng-fullstack gives you the best of the latest: Node, Go, HTTP/2, Angular 1, Angular 2, Vue, Aurelia, Express, Koa, Echo, Gin, MongoDB, Gulp, Babel, Typescript and much more.",
    "license": "MIT",
    "main": "app/index.js",
    "repository": "ericmdantas/generator-ng-fullstack",
    "author": {
        "name": "Eric Mendes Dantas",
        "url": "https://github.com/ericmdantas"
    },
    "engines": {
        "node": "stable"
    },
    "scripts": {
        "lint": "eslint _ng/**/*",
        "test": "npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register",
        "test-ci": "npm run lint && babel-node ./node_modules/istanbul/lib/cli cover ./node_modules/.bin/_mocha test/  --report lcovonly -- --recursive -R min --check-leaks --require babel-core/register && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "preversion": "npm t",
        "prepublish": "npm t"
    },
    "keywords": [
        "yeoman-generator",
        "angular-generator",
        "next generation",
        "ng-fullstack",
        "generator-angular-fullstack",
        "generator-ng-fullstack",
        "generator-iojs-fullstack",
        "angular",
        "angularjs",
        "angular2",
        "mongodb",
        "generator-fullstack",
        "fullstack",
        "go",
        "http2",
        "node-http2",
        "go-http2",
        "ng2",
        "go-generator",
        "generator-go",
        "generator-http2",
        "generator-ng2",
        "generator-go-fullstack"
    ],
    "dependencies": {
        "chalk": "^1.0.0",
        "lodash": "^4.13.1",
        "yeoman-generator": "^0.19.2",
        "yosay": "^1.2.0"
    },
    "devDependencies": {
        "babel": "^6.5.2",
        "babel-cli": "^6.7.7",
        "babel-core": "^6.7.7",
        "babel-preset-es2015": "^6.6.0",
        "chai": "^3.3.0",
        "coveralls": "^2.11.8",
        "eslint": "^3.0.1",
        "gulp": "^3.9.0",
        "gulp-rename": "^1.2.2",
        "istanbul": "^1.0.0-alpha.2",
        "mocha": "*",
        "mocha-lcov-reporter": "^1.2.0",
        "sinon": "^1.17.1",
        "sinon-chai": "^2.8.0"
    },
    "babel": {
        "presets": [
            "es2015"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
