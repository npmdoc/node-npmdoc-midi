# npmdoc-midi

#### api documentation for  midi (v0.9.5)  [![npm package](https://img.shields.io/npm/v/npmdoc-midi.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-midi) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-midi.svg)](https://travis-ci.org/npmdoc/node-npmdoc-midi)

#### MIDI hardware IO

[![NPM](https://nodei.co/npm/midi.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/midi)

- [https://npmdoc.github.io/node-npmdoc-midi/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-midi/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-midi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-midi/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-midi/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-midi/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "midi",
    "version": "0.9.5",
    "scripts": {
        "test": "mocha test/unit-tests.js && node test/virtual-loopback-test-automated.js"
    },
    "main": "midi.js",
    "description": "MIDI hardware IO",
    "author": {
        "name": "Justin Latimer",
        "url": "http://www.justinlatimer.com/"
    },
    "contributors": [
        {
            "name": "Elijah Insua"
        },
        {
            "name": "Andrew Morton"
        },
        {
            "name": "Luc Deschenaux"
        },
        {
            "name": "Michael Alyn Miller"
        },
        {
            "name": "Hugo Hromic"
        }
    ],
    "engines": {
        "node": ">=0.8.0"
    },
    "dependencies": {
        "bindings": "~1.2.1",
        "nan": "^2.3.3"
    },
    "devDependencies": {
        "mocha": ">= 2.1.0",
        "should": ">= 5.0.1"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/justinlatimer/node-midi.git"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
