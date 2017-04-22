# npmtest-react-codemod

#### basic test coverage for  react-codemod (v4.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-react-codemod.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-codemod) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-codemod.svg)](https://travis-ci.org/npmtest/node-npmtest-react-codemod)

#### React codemod scripts

[![NPM](https://nodei.co/npm/react-codemod.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-codemod)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-codemod/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-codemod/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-codemod/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-codemod/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-codemod/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-codemod/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-codemod/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-codemod/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-codemod/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-codemod/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-codemod/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-codemod/build/test-report.html](https://npmtest.github.io/node-npmtest-react-codemod/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-codemod/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-codemod/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-codemod/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-codemod/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-codemod/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-codemod/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-codemod/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-codemod/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-codemod",
    "version": "4.0.0",
    "description": "React codemod scripts",
    "license": "BSD-3-Clause",
    "repository": "reactjs/react-codemod",
    "scripts": {
        "test": "f() { EXIT=0; npm run lint || EXIT=$?; NODE_ENV=test jest $@ || EXIT=$?; exit $EXIT; }; f",
        "lint": "eslint ."
    },
    "dependencies": {
        "jscodeshift": "^0.3.25",
        "babel-eslint": "^6.0.5",
        "babel-plugin-transform-object-rest-spread": "^6.6.5",
        "babel-preset-es2015": "^6.6.0",
        "babel-jest": "^13.0.0",
        "eslint": "^2.13.1",
        "fbjs-scripts": "^0.7.1",
        "jest-cli": "^13.0.0"
    },
    "jest": {
        "automock": false,
        "globals": {
            "baseDir": "../"
        },
        "testEnvironment": "node",
        "testPathDirs": [
            "transforms"
        ]
    },
    "devDependencies": {
        "eslint-plugin-react": "^5.2.2"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
