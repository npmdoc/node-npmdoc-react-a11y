# npmdoc-react-a11y

#### api documentation for  [react-a11y (v0.3.3)](https://github.com/reactjs/react-a11y/blob/latest/README.md)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-a11y.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-a11y) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-a11y.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-a11y)

#### Warns about potential accessibility issues with your React elements.

[![NPM](https://nodei.co/npm/react-a11y.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-a11y)

- [https://npmdoc.github.io/node-npmdoc-react-a11y/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-a11y/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-a11y/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-a11y/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-a11y/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-a11y/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-a11y",
    "version": "0.3.3",
    "description": "Warns about potential accessibility issues with your React elements.",
    "main": "./dist/index.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/reactjs/react-a11y.git"
    },
    "homepage": "https://github.com/reactjs/react-a11y/blob/latest/README.md",
    "bugs": "https://github.com/reactjs/react-a11y/issues",
    "scripts": {
        "test": "jsxhint . && karma start --single-run",
        "watch-tests": "npm test -- --watch",
        "prepublish": "babel lib --out-dir dist",
        "release": "release"
    },
    "authors": [
        "Ryan Florence",
        "Todd Kloots",
        "Angus Croll"
    ],
    "license": "MIT",
    "devDependencies": {
        "babel": "^5.2.17",
        "babel-core": "^5.2.17",
        "babel-loader": "^5.0.0",
        "jsx-loader": "^0.12.2",
        "jsxhint": "^0.8.1",
        "karma": "^0.13.3",
        "karma-chrome-launcher": "^0.1.7",
        "karma-cli": "0.0.4",
        "karma-firefox-launcher": "^0.1.3",
        "karma-mocha": "^0.1.10",
        "karma-sourcemap-loader": "^0.3.2",
        "karma-webpack": "^1.7.0",
        "mocha": "^2.0.1",
        "react": "^0.12 || ^0.13 || ^0.14",
        "react-dom": "^0.14.7",
        "rf-release": "0.4.0",
        "webpack": "^1.4.13"
    },
    "tags": [
        "accessibility",
        "react",
        "a11y"
    ],
    "keywords": [
        "accessibility",
        "react",
        "a11y"
    ],
    "dependencies": {
        "object.assign": "^4.0.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
