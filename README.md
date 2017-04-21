# npmtest-imagemin-jpegoptim

#### basic test coverage for  imagemin-jpegoptim (v5.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-imagemin-jpegoptim.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-imagemin-jpegoptim) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-imagemin-jpegoptim.svg)](https://travis-ci.org/npmtest/node-npmtest-imagemin-jpegoptim)

#### jpegoptim imagemin plugin

[![NPM](https://nodei.co/npm/imagemin-jpegoptim.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/imagemin-jpegoptim)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-imagemin-jpegoptim/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-imagemin-jpegoptim/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-imagemin-jpegoptim/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-imagemin-jpegoptim/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-imagemin-jpegoptim/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-imagemin-jpegoptim/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-imagemin-jpegoptim/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-imagemin-jpegoptim/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-imagemin-jpegoptim/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-imagemin-jpegoptim/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-imagemin-jpegoptim/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-imagemin-jpegoptim/build/test-report.html](https://npmtest.github.io/node-npmtest-imagemin-jpegoptim/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-imagemin-jpegoptim/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-imagemin-jpegoptim/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-imagemin-jpegoptim/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-imagemin-jpegoptim/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-imagemin-jpegoptim/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-imagemin-jpegoptim/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-imagemin-jpegoptim/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-imagemin-jpegoptim/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "imagemin-jpegoptim",
    "version": "5.0.0",
    "description": "jpegoptim imagemin plugin",
    "license": "MIT",
    "repository": "imagemin/imagemin-jpegoptim",
    "author": {
        "name": "Kevin Mårtensson",
        "url": "github.com/kevva"
    },
    "maintainers": [
        {
            "name": "Sindre Sorhus",
            "url": "sindresorhus.com"
        },
        {
            "name": "Shinnosuke Watanabe",
            "url": "github.com/shinnn"
        }
    ],
    "engines": {
        "node": ">=4"
    },
    "scripts": {
        "test": "xo && ava"
    },
    "files": [
        "index.js"
    ],
    "keywords": [
        "compress",
        "image",
        "imageminplugin",
        "img",
        "jpg",
        "minify",
        "optimize"
    ],
    "dependencies": {
        "execa": "^0.4.0",
        "is-jpg": "^1.0.0",
        "jpegoptim-bin": "^3.0.0"
    },
    "devDependencies": {
        "ava": "*",
        "is-progressive": "^3.0.0",
        "pify": "^2.3.0",
        "xo": "*"
    },
    "xo": {
        "esnext": true
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
