# npmtest-react-router-bootstrap

#### basic test coverage for  [react-router-bootstrap (v0.24.2)](https://github.com/react-bootstrap/react-router-bootstrap)  [![npm package](https://img.shields.io/npm/v/npmtest-react-router-bootstrap.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-router-bootstrap) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-router-bootstrap.svg)](https://travis-ci.org/npmtest/node-npmtest-react-router-bootstrap)

#### Integration between React Router and React-Bootstrap

[![NPM](https://nodei.co/npm/react-router-bootstrap.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-router-bootstrap)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-router-bootstrap/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-router-bootstrap/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-router-bootstrap/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-router-bootstrap/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-router-bootstrap/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-router-bootstrap/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-router-bootstrap/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-router-bootstrap/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-router-bootstrap/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-router-bootstrap/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-router-bootstrap/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-router-bootstrap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-router-bootstrap/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-router-bootstrap/build/test-report.html](https://npmtest.github.io/node-npmtest-react-router-bootstrap/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-router-bootstrap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-router-bootstrap/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-router-bootstrap/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-router-bootstrap/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-router-bootstrap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-router-bootstrap/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-router-bootstrap/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-router-bootstrap/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matt Smith"
    },
    "bugs": {
        "url": "https://github.com/react-bootstrap/react-router-bootstrap/issues"
    },
    "dependencies": {
        "prop-types": "^15.5.8"
    },
    "description": "Integration between React Router and React-Bootstrap",
    "devDependencies": {
        "babel-cli": "^6.11.4",
        "babel-core": "^6.11.4",
        "babel-eslint": "^6.1.2",
        "babel-loader": "^6.2.4",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-es2015-loose": "^7.0.0",
        "babel-preset-react": "^6.11.1",
        "babel-preset-stage-1": "^6.5.0",
        "babel-register": "^6.11.5",
        "bootstrap": "^3.3.7",
        "chai": "^3.5.0",
        "colors": "^1.1.2",
        "css-loader": "^0.23.1",
        "eslint": "^2.13.1",
        "eslint-config-airbnb": "^9.0.1",
        "eslint-plugin-babel": "^3.3.0",
        "eslint-plugin-import": "^1.11.1",
        "eslint-plugin-jsx-a11y": "^1.5.5",
        "eslint-plugin-mocha": "^4.1.0",
        "eslint-plugin-react": "^5.2.2",
        "file-loader": "^0.9.0",
        "history": "^2.1.2",
        "html-webpack-plugin": "^2.22.0",
        "karma": "^1.1.1",
        "karma-chrome-launcher": "^1.0.1",
        "karma-firefox-launcher": "^1.0.0",
        "karma-mocha": "^1.1.1",
        "karma-mocha-reporter": "^2.0.4",
        "karma-sinon-chai": "^1.2.3",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^1.7.0",
        "less": "^2.7.1",
        "less-loader": "^2.2.3",
        "lodash": "^4.14.0",
        "mocha": "^2.5.3",
        "react": "^15.2.1",
        "react-addons-test-utils": "^15.4.2",
        "react-bootstrap": "^0.30.0",
        "react-dom": "^15.2.1",
        "react-router-dom": "^4.0.0",
        "release-script": "^1.0.2",
        "rimraf": "^2.5.4",
        "shelljs": "^0.7.2",
        "sinon": "^1.17.4",
        "sinon-chai": "^2.8.0",
        "style-loader": "^0.13.1",
        "url-loader": "^0.5.7",
        "webpack": "^1.13.1",
        "webpack-dev-server": "^1.14.1",
        "yargs": "^4.8.1"
    },
    "directories": {},
    "dist": {
        "shasum": "b99f5fcca812989d703eacbf400bed0529d040ab",
        "tarball": "https://registry.npmjs.org/react-router-bootstrap/-/react-router-bootstrap-0.24.2.tgz"
    },
    "files": [
        "lib"
    ],
    "gitHead": "c206ac1acd2573f974e5f9bdbc5e6b5b18f5f753",
    "homepage": "https://github.com/react-bootstrap/react-router-bootstrap",
    "keywords": [
        "react",
        "react-router",
        "react-bootstrap"
    ],
    "license": "Apache-2.0",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "mtscout6"
        },
        {
            "name": "vespakoen"
        },
        {
            "name": "idolize"
        },
        {
            "name": "taion"
        },
        {
            "name": "monastic.panic"
        }
    ],
    "name": "react-router-bootstrap",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": ">=0.14.0",
        "react-router-dom": ">=4.0.0"
    },
    "release-script": {
        "bowerRepo": "git@github.com:react-bootstrap/react-router-bootstrap-bower.git"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/react-bootstrap/react-router-bootstrap.git"
    },
    "scripts": {
        "bower-prepare": "babel-node scripts/bower-prepare.js",
        "build": "rimraf lib && babel src -d lib && webpack && webpack -p && npm run bower-prepare",
        "lint": "eslint scripts src test *.js",
        "release": "release",
        "tdd": "karma start",
        "test": "npm run lint && karma start --single-run",
        "visual-test": "open http://localhost:8080/ && webpack-dev-server --config webpack.visual.config.babel.js"
    },
    "version": "0.24.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
