# npmdoc-bezier-easing

#### api documentation for  [bezier-easing (v2.0.3)](https://github.com/gre/bezier-easing#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-bezier-easing.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-bezier-easing) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bezier-easing.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bezier-easing)

#### BezierEasing provides Cubic Bezier Curve easing which generalizes easing functions exactly like in CSS Transitions.

[![NPM](https://nodei.co/npm/bezier-easing.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bezier-easing)

- [https://npmdoc.github.io/node-npmdoc-bezier-easing/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bezier-easing/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bezier-easing/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bezier-easing/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-bezier-easing/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-bezier-easing/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gaëtan Renaudeau"
    },
    "bugs": {
        "url": "https://github.com/gre/bezier-easing/issues"
    },
    "dependencies": {},
    "description": "BezierEasing provides Cubic Bezier Curve easing which generalizes easing functions exactly like in CSS Transitions.",
    "devDependencies": {
        "assert": "^1.3.0",
        "benchmark": "^2.1.0",
        "browserify": "^13.0.0",
        "budo": "^8.1.0",
        "mocha": "^2.4.5",
        "uglify-js": "^2.6.2"
    },
    "directories": {},
    "dist": {
        "shasum": "cb493fddb7f8920ecca00973344ce0518885f17e",
        "tarball": "https://registry.npmjs.org/bezier-easing/-/bezier-easing-2.0.3.tgz"
    },
    "files": [
        "src",
        "dist"
    ],
    "gitHead": "18f06f5d058184690f5975a243e5bcfcba2e89c4",
    "homepage": "https://github.com/gre/bezier-easing#readme",
    "keywords": [
        "cubic-bezier",
        "bezier",
        "easing",
        "interpolation",
        "animation",
        "timing",
        "timing-function"
    ],
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "gre"
        }
    ],
    "name": "bezier-easing",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/gre/bezier-easing.git"
    },
    "scripts": {
        "benchmark": "node benchmark.js",
        "build-dev": "browserify --standalone BezierEasing src/index.js > dist/bezier-easing.js",
        "build-prod": "browserify --standalone BezierEasing src/index.js | uglifyjs -cm > dist/bezier-easing.min.js",
        "prepublish": "rm -rf dist && mkdir -p dist && npm run build-dev && npm run build-prod",
        "test": "mocha",
        "visual": "budo visual-demo.js"
    },
    "version": "2.0.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
