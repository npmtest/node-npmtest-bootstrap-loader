# npmtest-bootstrap-loader

#### basic test coverage for  [bootstrap-loader (v2.0.0)](https://github.com/shakacode/bootstrap-loader#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-bootstrap-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bootstrap-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bootstrap-loader.svg)](https://travis-ci.org/npmtest/node-npmtest-bootstrap-loader)

#### Boostrap for Webpack

[![NPM](https://nodei.co/npm/bootstrap-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bootstrap-loader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bootstrap-loader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bootstrap-loader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bootstrap-loader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bootstrap-loader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bootstrap-loader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bootstrap-loader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bootstrap-loader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bootstrap-loader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bootstrap-loader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bootstrap-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bootstrap-loader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bootstrap-loader/build/test-report.html](https://npmtest.github.io/node-npmtest-bootstrap-loader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bootstrap-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bootstrap-loader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bootstrap-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bootstrap-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bootstrap-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bootstrap-loader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bootstrap-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bootstrap-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Justin Gordon <justin.gordon@gmail.com> (https://github.com/justin808)",
        "Alex Fedoseev <alex.fedoseev@gmail.com> (https://github.com/alexfedoseev)"
    ],
    "bugs": {
        "url": "https://github.com/shakacode/bootstrap-loader/issues"
    },
    "dependencies": {
        "chalk": "^1.1.3",
        "escape-regexp": "0.0.1",
        "exports-loader": "^0.6.3",
        "js-yaml": "^3.7.0",
        "loader-utils": "^1.0.2",
        "resolve": "^1.1.7",
        "semver": "^5.3.0",
        "strip-json-comments": "^2.0.1"
    },
    "description": "Boostrap for Webpack",
    "devDependencies": {
        "babel": "^6.5.2",
        "babel-cli": "^6.18.0",
        "babel-preset-es2015": "^6.18.0",
        "babel-tape-runner": "^2.0.1",
        "eslint": "^3.10.2",
        "eslint-config-shakacode": "13.2.1",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^2.2.3",
        "eslint-plugin-react": "^6.6.0",
        "extract-text-webpack-plugin": "^2.1.0",
        "tap-spec": "^4.1.1",
        "tape": "^4.6.3",
        "webpack": "^2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "abccc0e57834c96520e04f971c9dcc483f508937",
        "tarball": "https://registry.npmjs.org/bootstrap-loader/-/bootstrap-loader-2.0.0.tgz"
    },
    "gitHead": "9f5f74dd872fa9776495790a083bb61831898024",
    "homepage": "https://github.com/shakacode/bootstrap-loader#readme",
    "keywords": [
        "bootstrap",
        "twitter"
    ],
    "license": "MIT",
    "main": "loader.js",
    "maintainers": [
        {
            "name": "alex.fedoseev"
        },
        {
            "name": "justin808"
        },
        {
            "name": "shakacode"
        }
    ],
    "name": "bootstrap-loader",
    "optionalDependencies": {},
    "peerDependencies": {
        "css-loader": "*",
        "extract-text-webpack-plugin": ">=2.1.0",
        "node-sass": "*",
        "resolve-url-loader": "*",
        "sass-loader": "*",
        "url-loader": "*",
        "webpack": ">=2.2.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/shakacode/bootstrap-loader.git"
    },
    "scripts": {
        "build": "babel --out-dir lib src",
        "clean": "rm -rf lib",
        "dev": "babel --watch --out-dir lib src",
        "lint": "eslint --ext .js .",
        "prepublish": "npm run prerelease",
        "prerelease": "npm run lint && npm run clean && npm run build",
        "preversion": "npm run prerelease",
        "release:major": "scripts/release major",
        "release:minor": "scripts/release minor",
        "release:patch": "scripts/release patch",
        "start": "npm run lint && npm run clean && npm run dev",
        "test": "babel-tape-runner node_package/tests/**/*.test.js | tap-spec"
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
