# npmtest-telegram-bot-bootstrap

#### basic test coverage for  [telegram-bot-bootstrap (v0.0.15)](https://github.com/kengz/telegram-bot-bootstrap)  [![npm package](https://img.shields.io/npm/v/npmtest-telegram-bot-bootstrap.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-telegram-bot-bootstrap) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-telegram-bot-bootstrap.svg)](https://travis-ci.org/npmtest/node-npmtest-telegram-bot-bootstrap)

#### A bootstrap for Telegram bot with directly deployable sample bot and JS-wrapped API methods.

[![NPM](https://nodei.co/npm/telegram-bot-bootstrap.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/telegram-bot-bootstrap)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-telegram-bot-bootstrap/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-telegram-bot-bootstrap/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-telegram-bot-bootstrap/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-telegram-bot-bootstrap/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-telegram-bot-bootstrap/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-telegram-bot-bootstrap/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-telegram-bot-bootstrap/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-telegram-bot-bootstrap/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-telegram-bot-bootstrap/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-telegram-bot-bootstrap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-telegram-bot-bootstrap/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-telegram-bot-bootstrap/build/test-report.html](https://npmtest.github.io/node-npmtest-telegram-bot-bootstrap/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-telegram-bot-bootstrap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-telegram-bot-bootstrap/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-telegram-bot-bootstrap/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-telegram-bot-bootstrap/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-telegram-bot-bootstrap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-telegram-bot-bootstrap/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-telegram-bot-bootstrap/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-telegram-bot-bootstrap/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "telegram-bot-bootstrap",
    "version": "0.0.15",
    "description": "A bootstrap for Telegram bot with directly deployable sample bot and JS-wrapped API methods.",
    "main": "API.js",
    "scripts": {
        "start": "node index.js",
        "test": "./node_modules/.bin/_mocha -u tdd -R spec"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/kengz/telegram-bot-bootstrap.git"
    },
    "keywords": [
        "Telegram",
        "bot",
        "Telegram bot",
        "nodeJS",
        "API",
        "bootstrap",
        "template",
        "sample",
        "Heroku"
    ],
    "author": "kengz",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/kengz/telegram-bot-bootstrap/issues"
    },
    "homepage": "https://github.com/kengz/telegram-bot-bootstrap",
    "dependencies": {
        "body-parser": "^1.13.2",
        "ejs": "^2.3.1",
        "express": "^4.13.1",
        "lomath": "^0.1.6",
        "morgan": "^1.6.1",
        "multer": "^0.1.8",
        "q": "^1.4.1",
        "reqscraper": "0.0.2",
        "request": "^2.58.0"
    },
    "devDependencies": {
        "chai": "^3.0.0",
        "dokker": "^0.1.1",
        "mocha": "^2.2.5"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
