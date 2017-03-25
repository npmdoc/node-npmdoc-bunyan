# api documentation for  [bunyan (v1.8.9)](https://github.com/trentm/node-bunyan#readme)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bunyan.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bunyan)
#### a JSON logging library for node.js services

[![NPM](https://nodei.co/npm/bunyan.png?downloads=true)](https://www.npmjs.com/package/bunyan)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bunyan/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-bunyan_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bunyan/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-bunyan/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "// dtrace-provider": "required for dtrace features",
    "// moment": "required for local time with CLI",
    "// mv": "required for RotatingFileStream",
    "author": {
        "name": "Trent Mick",
        "email": "trentm@gmail.com",
        "url": "http://trentm.com"
    },
    "bin": {
        "bunyan": "./bin/bunyan"
    },
    "bugs": {
        "url": "https://github.com/trentm/node-bunyan/issues"
    },
    "contributors": [
        {
            "name": "Trent Mick",
            "url": "http://trentm.com"
        },
        {
            "name": "Mark Cavage",
            "url": "https://github.com/mcavage"
        },
        {
            "name": "Dave Pacheco",
            "url": "https://github.com/davepacheco"
        },
        {
            "name": "Michael Hart",
            "url": "https://github.com/mhart"
        },
        {
            "name": "Isaac Schlueter",
            "url": "https://github.com/isaacs"
        },
        {
            "name": "Rob Gulewich",
            "url": "https://github.com/rgulewich"
        },
        {
            "name": "Bryan Cantrill",
            "url": "https://github.com/bcantrill"
        },
        {
            "name": "Michael Hart",
            "url": "https://github.com/mhart"
        },
        {
            "name": "Simon Wade",
            "url": "https://github.com/aexmachina"
        },
        {
            "name": "https://github.com/glenn-murray-bse"
        },
        {
            "name": "Chakrit Wichian",
            "url": "https://github.com/chakrit"
        },
        {
            "name": "Patrick Mooney",
            "url": "https://github.com/pfmooney"
        },
        {
            "name": "Johan Nordberg",
            "url": "https://github.com/jnordberg"
        },
        {
            "name": "https://github.com/timborodin"
        },
        {
            "name": "Ryan Graham",
            "url": "https://github.com/rmg"
        },
        {
            "name": "Alex Kocharin",
            "url": "https://github.com/rlidwka"
        },
        {
            "name": "Andrei Neculau",
            "url": "https://github.com/andreineculau"
        },
        {
            "name": "Mihai Tomescu",
            "url": "https://github.com/matomesc"
        },
        {
            "name": "Daniel Juhl",
            "url": "https://github.com/danieljuhl"
        },
        {
            "name": "Chris Barber",
            "url": "https://github.com/cb1kenobi"
        },
        {
            "name": "Manuel Schneider",
            "url": "https://github.com/manuelschneider"
        },
        {
            "name": "Martin Gausby",
            "url": "https://github.com/gausby"
        },
        {
            "name": "Stéphan Kochen",
            "url": "https://github.com/stephank"
        },
        {
            "name": "Shakeel Mohamed",
            "url": "https://github.com/shakeelmohamed"
        },
        {
            "name": "Denis Izmaylov",
            "url": "https://github.com/DenisIzmaylov"
        },
        {
            "name": "Guillermo Grau Panea",
            "url": "https://github.com/guigrpa"
        },
        {
            "name": "Mark LeMerise",
            "url": "https://github.com/MarkLeMerise"
        },
        {
            "name": "https://github.com/sometimesalready"
        },
        {
            "name": "Charly Koza",
            "url": "https://github.com/Cactusbone"
        },
        {
            "name": "Thomas Heymann",
            "url": "https://github.com/cyberthom"
        },
        {
            "name": "David M. Lee",
            "url": "https://github.com/leedm777"
        },
        {
            "name": "Marc Udoff",
            "url": "https://github.com/mlucool"
        },
        {
            "name": "Mark Stosberg",
            "url": "https://github.com/markstos"
        },
        {
            "name": "Alexander Ray",
            "url": "https://github.com/aray12"
        },
        {
            "name": "Adam Lynch",
            "url": "https://github.com/adam-lynch"
        },
        {
            "name": "Michael Nisi",
            "url": "https://github.com/michaelnisi"
        },
        {
            "name": "Martijn Schrage",
            "url": "https://github.com/Oblosys"
        },
        {
            "name": "Paul Milham",
            "url": "https://github.com/domrein"
        },
        {
            "name": "Frankie O'Rourke",
            "url": "https://github.com/psfrankie"
        },
        {
            "name": "Cody Mello",
            "url": "https://github.com/melloc"
        },
        {
            "name": "Todd Whiteman",
            "url": "https://github.com/twhiteman"
        },
        {
            "name": "Zach Bjornson",
            "url": "https://github.com/zbjornson"
        }
    ],
    "dependencies": {
        "dtrace-provider": "~0.8",
        "moment": "^2.10.6",
        "mv": "~2",
        "safe-json-stringify": "~1"
    },
    "description": "a JSON logging library for node.js services",
    "devDependencies": {
        "ben": "0.0.0",
        "markdown-toc": "0.12.x",
        "nodeunit": "0.9",
        "vasync": "1.4.3",
        "verror": "1.3.3"
    },
    "directories": {},
    "dist": {
        "shasum": "2c7c9d422ea64ee2465d52b4decd72de0657401a",
        "tarball": "https://registry.npmjs.org/bunyan/-/bunyan-1.8.9.tgz"
    },
    "engines": [
        "node >=0.10.0"
    ],
    "gitHead": "34f4469a25521c2555294ec71c79ba67fd4b713b",
    "homepage": "https://github.com/trentm/node-bunyan#readme",
    "keywords": [
        "log",
        "logging",
        "log4j",
        "json",
        "bunyan"
    ],
    "license": "MIT",
    "main": "./lib/bunyan.js",
    "maintainers": [
        {
            "name": "trentm",
            "email": "trentm@gmail.com"
        }
    ],
    "name": "bunyan",
    "optionalDependencies": {
        "dtrace-provider": "~0.8",
        "moment": "^2.10.6",
        "mv": "~2",
        "safe-json-stringify": "~1"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/trentm/node-bunyan.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "1.8.9"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module bunyan](#apidoc.module.bunyan)
1.  [function <span class="apidocSignatureSpan">bunyan.</span>RingBuffer (options)](#apidoc.element.bunyan.RingBuffer)
1.  [function <span class="apidocSignatureSpan">bunyan.</span>RotatingFileStream (options)](#apidoc.element.bunyan.RotatingFileStream)
1.  [function <span class="apidocSignatureSpan">bunyan.</span>createLogger (options)](#apidoc.element.bunyan.createLogger)
1.  [function <span class="apidocSignatureSpan">bunyan.</span>resolveLevel (nameOrNum)](#apidoc.element.bunyan.resolveLevel)
1.  [function <span class="apidocSignatureSpan">bunyan.</span>safeCycles ()](#apidoc.element.bunyan.safeCycles)
1.  [function <span class="apidocSignatureSpan">bunyan.</span>super_ ()](#apidoc.element.bunyan.super_)
1.  number <span class="apidocSignatureSpan">bunyan.</span>DEBUG
1.  number <span class="apidocSignatureSpan">bunyan.</span>ERROR
1.  number <span class="apidocSignatureSpan">bunyan.</span>FATAL
1.  number <span class="apidocSignatureSpan">bunyan.</span>INFO
1.  number <span class="apidocSignatureSpan">bunyan.</span>LOG_VERSION
1.  number <span class="apidocSignatureSpan">bunyan.</span>TRACE
1.  number <span class="apidocSignatureSpan">bunyan.</span>WARN
1.  object <span class="apidocSignatureSpan">bunyan.</span>RingBuffer.prototype
1.  object <span class="apidocSignatureSpan">bunyan.</span>RotatingFileStream.prototype
1.  object <span class="apidocSignatureSpan">bunyan.</span>levelFromName
1.  object <span class="apidocSignatureSpan">bunyan.</span>nameFromLevel
1.  object <span class="apidocSignatureSpan">bunyan.</span>stdSerializers
1.  string <span class="apidocSignatureSpan">bunyan.</span>VERSION

#### [module bunyan.RingBuffer](#apidoc.module.bunyan.RingBuffer)
1.  [function <span class="apidocSignatureSpan">bunyan.</span>RingBuffer (options)](#apidoc.element.bunyan.RingBuffer.RingBuffer)
1.  [function <span class="apidocSignatureSpan">bunyan.RingBuffer.</span>super_ ()](#apidoc.element.bunyan.RingBuffer.super_)

#### [module bunyan.RingBuffer.prototype](#apidoc.module.bunyan.RingBuffer.prototype)
1.  [function <span class="apidocSignatureSpan">bunyan.RingBuffer.prototype.</span>destroy ()](#apidoc.element.bunyan.RingBuffer.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">bunyan.RingBuffer.prototype.</span>destroySoon ()](#apidoc.element.bunyan.RingBuffer.prototype.destroySoon)
1.  [function <span class="apidocSignatureSpan">bunyan.RingBuffer.prototype.</span>end ()](#apidoc.element.bunyan.RingBuffer.prototype.end)
1.  [function <span class="apidocSignatureSpan">bunyan.RingBuffer.prototype.</span>write (record)](#apidoc.element.bunyan.RingBuffer.prototype.write)

#### [module bunyan.RotatingFileStream](#apidoc.module.bunyan.RotatingFileStream)
1.  [function <span class="apidocSignatureSpan">bunyan.</span>RotatingFileStream (options)](#apidoc.element.bunyan.RotatingFileStream.RotatingFileStream)
1.  [function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.</span>super_ ()](#apidoc.element.bunyan.RotatingFileStream.super_)

#### [module bunyan.RotatingFileStream.prototype](#apidoc.module.bunyan.RotatingFileStream.prototype)
1.  [function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>_calcRotTime (periodOffset)](#apidoc.element.bunyan.RotatingFileStream.prototype._calcRotTime)
1.  [function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>_debug ()](#apidoc.element.bunyan.RotatingFileStream.prototype._debug)
1.  [function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>_setRotationTimer ()](#apidoc.element.bunyan.RotatingFileStream.prototype._setRotationTimer)
1.  [function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>_setupNextRot ()](#apidoc.element.bunyan.RotatingFileStream.prototype._setupNextRot)
1.  [function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>destroy (s)](#apidoc.element.bunyan.RotatingFileStream.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>destroySoon (s)](#apidoc.element.bunyan.RotatingFileStream.prototype.destroySoon)
1.  [function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>end (s)](#apidoc.element.bunyan.RotatingFileStream.prototype.end)
1.  [function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>rotate ()](#apidoc.element.bunyan.RotatingFileStream.prototype.rotate)
1.  [function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>write (s)](#apidoc.element.bunyan.RotatingFileStream.prototype.write)

#### [module bunyan.stdSerializers](#apidoc.module.bunyan.stdSerializers)
1.  [function <span class="apidocSignatureSpan">bunyan.stdSerializers.</span>err (err)](#apidoc.element.bunyan.stdSerializers.err)
1.  [function <span class="apidocSignatureSpan">bunyan.stdSerializers.</span>req (req)](#apidoc.element.bunyan.stdSerializers.req)
1.  [function <span class="apidocSignatureSpan">bunyan.stdSerializers.</span>res (res)](#apidoc.element.bunyan.stdSerializers.res)



# <a name="apidoc.module.bunyan"></a>[module bunyan](#apidoc.module.bunyan)

#### <a name="apidoc.element.bunyan.RingBuffer"></a>[function <span class="apidocSignatureSpan">bunyan.</span>RingBuffer (options)](#apidoc.element.bunyan.RingBuffer)
- description and source-code
```javascript
function RingBuffer(options) {
    this.limit = options && options.limit ? options.limit : 100;
    this.writable = true;
    this.records = [];
    EventEmitter.call(this);
}
```
- example usage
```shell
...
own HTTP interface, or a post-mortem facility like MDB or node-panic.

To use a RingBuffer:

'''js
/* Create a ring buffer that stores the last 100 records. */
var bunyan = require('bunyan');
var ringbuffer = new bunyan.RingBuffer({ limit: 100 });
var log = bunyan.createLogger({
name: 'foo',
streams: [
    {
        level: 'info',
        stream: process.stdout
    },
...
```

#### <a name="apidoc.element.bunyan.RotatingFileStream"></a>[function <span class="apidocSignatureSpan">bunyan.</span>RotatingFileStream (options)](#apidoc.element.bunyan.RotatingFileStream)
- description and source-code
```javascript
function RotatingFileStream(options) {
    this.path = options.path;

    this.count = (options.count == null ? 10 : options.count);
    assert.equal(typeof (this.count), 'number',
        format('rotating-file stream "count" is not a number: %j (%s) in %j',
            this.count, typeof (this.count), this));
    assert.ok(this.count >= 0,
        format('rotating-file stream "count" is not >= 0: %j in %j',
            this.count, this));

    // Parse 'options.period'.
    if (options.period) {
        // <number><scope> where scope is:
        //    h   hours (at the start of the hour)
        //    d   days (at the start of the day, i.e. just after midnight)
        //    w   weeks (at the start of Sunday)
        //    m   months (on the first of the month)
        //    y   years (at the start of Jan 1st)
        // with special values 'hourly' (1h), 'daily' (1d), "weekly" (1w),
        // 'monthly' (1m) and 'yearly' (1y)
        var period = {
            'hourly': '1h',
            'daily': '1d',
            'weekly': '1w',
            'monthly': '1m',
            'yearly': '1y'
        }[options.period] || options.period;
        var m = /^([1-9][0-9]*)([hdwmy]|ms)$/.exec(period);
        if (!m) {
            throw new Error(format('invalid period: "%s"', options.period));
        }
        this.periodNum = Number(m[1]);
        this.periodScope = m[2];
    } else {
        this.periodNum = 1;
        this.periodScope = 'd';
    }

    var lastModified = null;
    try {
        var fileInfo = fs.statSync(this.path);
        lastModified = fileInfo.mtime.getTime();
    }
    catch (err) {
        // file doesn't exist
    }
    var rotateAfterOpen = false;
    if (lastModified) {
        var lastRotTime = this._calcRotTime(0);
        if (lastModified < lastRotTime) {
            rotateAfterOpen = true;
        }
    }

    // TODO: template support for backup files
    // template: <path to which to rotate>
    //      default is %P.%n
    //      '/var/log/archive/foo.log'  -> foo.log.%n
    //      '/var/log/archive/foo.log.%n'
    //      codes:
    //          XXX support strftime codes (per node version of those)
    //              or whatever module. Pick non-colliding for extra
    //              codes
    //          %P      'path' base value
    //          %n      integer number of rotated log (1,2,3,...)
    //          %d      datetime in YYYY-MM-DD_HH-MM-SS
    //                      XXX what should default date format be?
    //                          prior art? Want to avoid ':' in
    //                          filenames (illegal on Windows for one).

    this.stream = fs.createWriteStream(this.path,
        {flags: 'a', encoding: 'utf8'});

    this.rotQueue = [];
    this.rotating = false;
    if (rotateAfterOpen) {
        this._debug('rotateAfterOpen -> call rotate()');
        this.rotate();
    } else {
        this._setupNextRot();
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.createLogger"></a>[function <span class="apidocSignatureSpan">bunyan.</span>createLogger (options)](#apidoc.element.bunyan.createLogger)
- description and source-code
```javascript
function createLogger(options) {
    return new Logger(options);
}
```
- example usage
```shell
...
[![npm version](https://img.shields.io/npm/v/bunyan.svg?style=flat)](https://www.npmjs.com/package/bunyan)
[![Build Status](https://travis-ci.org/trentm/node-bunyan.svg?branch=master)](https://travis-ci.org/trentm/node-bunyan)

Bunyan is **a simple and fast JSON logging library** for node.js services:

'''js
var bunyan = require('bunyan');
var log = bunyan.createLogger({name: "myapp"});
log.info("hi");
'''

and **a 'bunyan' CLI tool** for nicely viewing those logs:

![bunyan CLI screenshot](https://raw.github.com/trentm/node-bunyan/master/tools/screenshot1.png)
...
```

#### <a name="apidoc.element.bunyan.resolveLevel"></a>[function <span class="apidocSignatureSpan">bunyan.</span>resolveLevel (nameOrNum)](#apidoc.element.bunyan.resolveLevel)
- description and source-code
```javascript
function resolveLevel(nameOrNum) {
    var level;
    var type = typeof (nameOrNum);
    if (type === 'string') {
        level = levelFromName[nameOrNum.toLowerCase()];
        if (!level) {
            throw new Error(format('unknown level name: "%s"', nameOrNum));
        }
    } else if (type !== 'number') {
        throw new TypeError(format('cannot resolve level: invalid arg (%s):',
            type, nameOrNum));
    } else if (nameOrNum < 0 || Math.floor(nameOrNum) !== nameOrNum) {
        throw new TypeError(format('level is not a positive integer: %s',
            nameOrNum));
    } else {
        level = nameOrNum;
    }
    return level;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.safeCycles"></a>[function <span class="apidocSignatureSpan">bunyan.</span>safeCycles ()](#apidoc.element.bunyan.safeCycles)
- description and source-code
```javascript
function safeCyclesSet() {
    var seen = new Set();
    return function (key, val) {
        if (!val || typeof (val) !== 'object') {
            return val;
        }
        if (seen.has(val)) {
            return '[Circular]';
        }
        seen.add(val);
        return val;
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.super_"></a>[function <span class="apidocSignatureSpan">bunyan.</span>super_ ()](#apidoc.element.bunyan.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bunyan.RingBuffer"></a>[module bunyan.RingBuffer](#apidoc.module.bunyan.RingBuffer)

#### <a name="apidoc.element.bunyan.RingBuffer.RingBuffer"></a>[function <span class="apidocSignatureSpan">bunyan.</span>RingBuffer (options)](#apidoc.element.bunyan.RingBuffer.RingBuffer)
- description and source-code
```javascript
function RingBuffer(options) {
    this.limit = options && options.limit ? options.limit : 100;
    this.writable = true;
    this.records = [];
    EventEmitter.call(this);
}
```
- example usage
```shell
...
own HTTP interface, or a post-mortem facility like MDB or node-panic.

To use a RingBuffer:

'''js
/* Create a ring buffer that stores the last 100 records. */
var bunyan = require('bunyan');
var ringbuffer = new bunyan.RingBuffer({ limit: 100 });
var log = bunyan.createLogger({
name: 'foo',
streams: [
    {
        level: 'info',
        stream: process.stdout
    },
...
```

#### <a name="apidoc.element.bunyan.RingBuffer.super_"></a>[function <span class="apidocSignatureSpan">bunyan.RingBuffer.</span>super_ ()](#apidoc.element.bunyan.RingBuffer.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bunyan.RingBuffer.prototype"></a>[module bunyan.RingBuffer.prototype](#apidoc.module.bunyan.RingBuffer.prototype)

#### <a name="apidoc.element.bunyan.RingBuffer.prototype.destroy"></a>[function <span class="apidocSignatureSpan">bunyan.RingBuffer.prototype.</span>destroy ()](#apidoc.element.bunyan.RingBuffer.prototype.destroy)
- description and source-code
```javascript
destroy = function () {
    this.writable = false;
    this.emit('close');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.RingBuffer.prototype.destroySoon"></a>[function <span class="apidocSignatureSpan">bunyan.RingBuffer.prototype.</span>destroySoon ()](#apidoc.element.bunyan.RingBuffer.prototype.destroySoon)
- description and source-code
```javascript
destroySoon = function () {
    this.destroy();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.RingBuffer.prototype.end"></a>[function <span class="apidocSignatureSpan">bunyan.RingBuffer.prototype.</span>end ()](#apidoc.element.bunyan.RingBuffer.prototype.end)
- description and source-code
```javascript
end = function () {
    if (arguments.length > 0)
        this.write.apply(this, Array.prototype.slice.call(arguments));
    this.writable = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.RingBuffer.prototype.write"></a>[function <span class="apidocSignatureSpan">bunyan.RingBuffer.prototype.</span>write (record)](#apidoc.element.bunyan.RingBuffer.prototype.write)
- description and source-code
```javascript
write = function (record) {
    if (!this.writable)
        throw (new Error('RingBuffer has been ended already'));

    this.records.push(record);

    if (this.records.length > this.limit)
        this.records.shift();

    return (true);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bunyan.RotatingFileStream"></a>[module bunyan.RotatingFileStream](#apidoc.module.bunyan.RotatingFileStream)

#### <a name="apidoc.element.bunyan.RotatingFileStream.RotatingFileStream"></a>[function <span class="apidocSignatureSpan">bunyan.</span>RotatingFileStream (options)](#apidoc.element.bunyan.RotatingFileStream.RotatingFileStream)
- description and source-code
```javascript
function RotatingFileStream(options) {
    this.path = options.path;

    this.count = (options.count == null ? 10 : options.count);
    assert.equal(typeof (this.count), 'number',
        format('rotating-file stream "count" is not a number: %j (%s) in %j',
            this.count, typeof (this.count), this));
    assert.ok(this.count >= 0,
        format('rotating-file stream "count" is not >= 0: %j in %j',
            this.count, this));

    // Parse 'options.period'.
    if (options.period) {
        // <number><scope> where scope is:
        //    h   hours (at the start of the hour)
        //    d   days (at the start of the day, i.e. just after midnight)
        //    w   weeks (at the start of Sunday)
        //    m   months (on the first of the month)
        //    y   years (at the start of Jan 1st)
        // with special values 'hourly' (1h), 'daily' (1d), "weekly" (1w),
        // 'monthly' (1m) and 'yearly' (1y)
        var period = {
            'hourly': '1h',
            'daily': '1d',
            'weekly': '1w',
            'monthly': '1m',
            'yearly': '1y'
        }[options.period] || options.period;
        var m = /^([1-9][0-9]*)([hdwmy]|ms)$/.exec(period);
        if (!m) {
            throw new Error(format('invalid period: "%s"', options.period));
        }
        this.periodNum = Number(m[1]);
        this.periodScope = m[2];
    } else {
        this.periodNum = 1;
        this.periodScope = 'd';
    }

    var lastModified = null;
    try {
        var fileInfo = fs.statSync(this.path);
        lastModified = fileInfo.mtime.getTime();
    }
    catch (err) {
        // file doesn't exist
    }
    var rotateAfterOpen = false;
    if (lastModified) {
        var lastRotTime = this._calcRotTime(0);
        if (lastModified < lastRotTime) {
            rotateAfterOpen = true;
        }
    }

    // TODO: template support for backup files
    // template: <path to which to rotate>
    //      default is %P.%n
    //      '/var/log/archive/foo.log'  -> foo.log.%n
    //      '/var/log/archive/foo.log.%n'
    //      codes:
    //          XXX support strftime codes (per node version of those)
    //              or whatever module. Pick non-colliding for extra
    //              codes
    //          %P      'path' base value
    //          %n      integer number of rotated log (1,2,3,...)
    //          %d      datetime in YYYY-MM-DD_HH-MM-SS
    //                      XXX what should default date format be?
    //                          prior art? Want to avoid ':' in
    //                          filenames (illegal on Windows for one).

    this.stream = fs.createWriteStream(this.path,
        {flags: 'a', encoding: 'utf8'});

    this.rotQueue = [];
    this.rotating = false;
    if (rotateAfterOpen) {
        this._debug('rotateAfterOpen -> call rotate()');
        this.rotate();
    } else {
        this._setupNextRot();
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.RotatingFileStream.super_"></a>[function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.</span>super_ ()](#apidoc.element.bunyan.RotatingFileStream.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bunyan.RotatingFileStream.prototype"></a>[module bunyan.RotatingFileStream.prototype](#apidoc.module.bunyan.RotatingFileStream.prototype)

#### <a name="apidoc.element.bunyan.RotatingFileStream.prototype._calcRotTime"></a>[function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>_calcRotTime (periodOffset)](#apidoc.element.bunyan.RotatingFileStream.prototype._calcRotTime)
- description and source-code
```javascript
function _calcRotTime(periodOffset) {
    this._debug('_calcRotTime: %s%s', this.periodNum, this.periodScope);
    var d = new Date();

    this._debug('  now local: %s', d);
    this._debug('    now utc: %s', d.toISOString());
    var rotAt;
    switch (this.periodScope) {
    case 'ms':
        // Hidden millisecond period for debugging.
        if (this.rotAt) {
            rotAt = this.rotAt + this.periodNum * periodOffset;
        } else {
            rotAt = Date.now() + this.periodNum * periodOffset;
        }
        break;
    case 'h':
        if (this.rotAt) {
            rotAt = this.rotAt + this.periodNum * 60 * 60 * 1000 * periodOffset;
        } else {
            // First time: top of the next hour.
            rotAt = Date.UTC(d.getUTCFullYear(), d.getUTCMonth(),
                d.getUTCDate(), d.getUTCHours() + periodOffset);
        }
        break;
    case 'd':
        if (this.rotAt) {
            rotAt = this.rotAt + this.periodNum * 24 * 60 * 60 * 1000
                * periodOffset;
        } else {
            // First time: start of tomorrow (i.e. at the coming midnight) UTC.
            rotAt = Date.UTC(d.getUTCFullYear(), d.getUTCMonth(),
                d.getUTCDate() + periodOffset);
        }
        break;
    case 'w':
        // Currently, always on Sunday morning at 00:00:00 (UTC).
        if (this.rotAt) {
            rotAt = this.rotAt + this.periodNum * 7 * 24 * 60 * 60 * 1000
                * periodOffset;
        } else {
            // First time: this coming Sunday.
            var dayOffset = (7 - d.getUTCDay());
            if (periodOffset < 1) {
                dayOffset = -d.getUTCDay();
            }
            if (periodOffset > 1 || periodOffset < -1) {
                dayOffset += 7 * periodOffset;
            }
            rotAt = Date.UTC(d.getUTCFullYear(), d.getUTCMonth(),
                d.getUTCDate() + dayOffset);
        }
        break;
    case 'm':
        if (this.rotAt) {
            rotAt = Date.UTC(d.getUTCFullYear(),
                d.getUTCMonth() + this.periodNum * periodOffset, 1);
        } else {
            // First time: the start of the next month.
            rotAt = Date.UTC(d.getUTCFullYear(),
                d.getUTCMonth() + periodOffset, 1);
        }
        break;
    case 'y':
        if (this.rotAt) {
            rotAt = Date.UTC(d.getUTCFullYear() + this.periodNum * periodOffset,
                0, 1);
        } else {
            // First time: the start of the next year.
            rotAt = Date.UTC(d.getUTCFullYear() + periodOffset, 0, 1);
        }
        break;
    default:
        assert.fail(format('invalid period scope: "%s"', this.periodScope));
    }

    if (this._debug()) {
        this._debug('  **rotAt**: %s (utc: %s)', rotAt,
            new Date(rotAt).toUTCString());
        var now = Date.now();
        this._debug('        now: %s (%sms == %smin == %sh to go)',
            now,
            rotAt - now,
            (rotAt-now)/1000/60,
            (rotAt-now)/1000/60/60);
    }
    return rotAt;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.RotatingFileStream.prototype._debug"></a>[function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>_debug ()](#apidoc.element.bunyan.RotatingFileStream.prototype._debug)
- description and source-code
```javascript
_debug = function () {
    // Set this to 'true' to add debug logging.
    if (false) {
        if (arguments.length === 0) {
            return true;
        }
        var args = Array.prototype.slice.call(arguments);
        args[0] = '[' + (new Date().toISOString()) + ', '
            + this.path + '] ' + args[0];
        console.log.apply(this, args);
    } else {
        return false;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.RotatingFileStream.prototype._setRotationTimer"></a>[function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>_setRotationTimer ()](#apidoc.element.bunyan.RotatingFileStream.prototype._setRotationTimer)
- description and source-code
```javascript
_setRotationTimer = function () {
    var self = this;
    var delay = this.rotAt - Date.now();
    // Cap timeout to Node's max setTimeout, see
    // <https://github.com/joyent/node/issues/8656>.
    var TIMEOUT_MAX = 2147483647; // 2^31-1
    if (delay > TIMEOUT_MAX) {
        delay = TIMEOUT_MAX;
    }
    this.timeout = setTimeout(
        function () {
            self._debug('_setRotationTimer timeout -> call rotate()');
            self.rotate();
        },
        delay);
    if (typeof (this.timeout.unref) === 'function') {
        this.timeout.unref();
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.RotatingFileStream.prototype._setupNextRot"></a>[function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>_setupNextRot ()](#apidoc.element.bunyan.RotatingFileStream.prototype._setupNextRot)
- description and source-code
```javascript
_setupNextRot = function () {
    this.rotAt = this._calcRotTime(1);
    this._setRotationTimer();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.RotatingFileStream.prototype.destroy"></a>[function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>destroy (s)](#apidoc.element.bunyan.RotatingFileStream.prototype.destroy)
- description and source-code
```javascript
function destroy(s) {
    this.stream.destroy();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.RotatingFileStream.prototype.destroySoon"></a>[function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>destroySoon (s)](#apidoc.element.bunyan.RotatingFileStream.prototype.destroySoon)
- description and source-code
```javascript
function destroySoon(s) {
    this.stream.destroySoon();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.RotatingFileStream.prototype.end"></a>[function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>end (s)](#apidoc.element.bunyan.RotatingFileStream.prototype.end)
- description and source-code
```javascript
function end(s) {
    this.stream.end();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.RotatingFileStream.prototype.rotate"></a>[function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>rotate ()](#apidoc.element.bunyan.RotatingFileStream.prototype.rotate)
- description and source-code
```javascript
function rotate() {
    // XXX What about shutdown?
    var self = this;

    // If rotation period is > ~25 days, we have to break into multiple
    // setTimeout's. See <https://github.com/joyent/node/issues/8656>.
    if (self.rotAt && self.rotAt > Date.now()) {
        return self._setRotationTimer();
    }

    this._debug('rotate');
    if (self.rotating) {
        throw new TypeError('cannot start a rotation when already rotating');
    }
    self.rotating = true;

    self.stream.end();  // XXX can do moves sync after this? test at high rate

    function del() {
        var toDel = self.path + '.' + String(n - 1);
        if (n === 0) {
            toDel = self.path;
        }
        n -= 1;
        self._debug('  rm %s', toDel);
        fs.unlink(toDel, function (delErr) {
            //XXX handle err other than not exists
            moves();
        });
    }

    function moves() {
        if (self.count === 0 || n < 0) {
            return finish();
        }
        var before = self.path;
        var after = self.path + '.' + String(n);
        if (n > 0) {
            before += '.' + String(n - 1);
        }
        n -= 1;
        fs.exists(before, function (exists) {
            if (!exists) {
                moves();
            } else {
                self._debug('  mv %s %s', before, after);
                mv(before, after, function (mvErr) {
                    if (mvErr) {
                        self.emit('error', mvErr);
                        finish(); // XXX finish here?
                    } else {
                        moves();
                    }
                });
            }
        })
    }

    function finish() {
        self._debug('  open %s', self.path);
        self.stream = fs.createWriteStream(self.path,
            {flags: 'a', encoding: 'utf8'});
        var q = self.rotQueue, len = q.length;
        for (var i = 0; i < len; i++) {
            self.stream.write(q[i]);
        }
        self.rotQueue = [];
        self.rotating = false;
        self.emit('drain');
        self._setupNextRot();
    }

    var n = this.count;
    del();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.RotatingFileStream.prototype.write"></a>[function <span class="apidocSignatureSpan">bunyan.RotatingFileStream.prototype.</span>write (s)](#apidoc.element.bunyan.RotatingFileStream.prototype.write)
- description and source-code
```javascript
function write(s) {
    if (this.rotating) {
        this.rotQueue.push(s);
        return false;
    } else {
        return this.stream.write(s);
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bunyan.stdSerializers"></a>[module bunyan.stdSerializers](#apidoc.module.bunyan.stdSerializers)

#### <a name="apidoc.element.bunyan.stdSerializers.err"></a>[function <span class="apidocSignatureSpan">bunyan.stdSerializers.</span>err (err)](#apidoc.element.bunyan.stdSerializers.err)
- description and source-code
```javascript
err = function (err) {
    if (!err || !err.stack)
        return err;
    var obj = {
        message: err.message,
        name: err.name,
        stack: getFullErrorStack(err),
        code: err.code,
        signal: err.signal
    }
    return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.stdSerializers.req"></a>[function <span class="apidocSignatureSpan">bunyan.stdSerializers.</span>req (req)](#apidoc.element.bunyan.stdSerializers.req)
- description and source-code
```javascript
req = function (req) {
    if (!req || !req.connection)
        return req;
    return {
        method: req.method,
        url: req.url,
        headers: req.headers,
        remoteAddress: req.connection.remoteAddress,
        remotePort: req.connection.remotePort
    };
    // Trailers: Skipping for speed. If you need trailers in your app, then
    // make a custom serializer.
    //if (Object.keys(trailers).length > 0) {
    //  obj.trailers = req.trailers;
    //}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bunyan.stdSerializers.res"></a>[function <span class="apidocSignatureSpan">bunyan.stdSerializers.</span>res (res)](#apidoc.element.bunyan.stdSerializers.res)
- description and source-code
```javascript
res = function (res) {
    if (!res || !res.statusCode)
        return res;
    return {
        statusCode: res.statusCode,
        header: res._header
    }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
