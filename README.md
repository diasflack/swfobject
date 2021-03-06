# swfobject-constructor

[![Made by unshift](https://img.shields.io/badge/made%20by-unshift-00ffcc.svg?style=flat-square)](http://unshift.io)[![Version npm](http://img.shields.io/npm/v/swfobject.svg?style=flat-square)](http://browsenpm.org/package/swfobject)[![IRC channel](http://img.shields.io/badge/IRC-irc.freenode.net%23unshift-00a8ff.svg?style=flat-square)](http://webchat.freenode.net/?channels=unshift)

This a browserify compatible version of the `swfobject` library which is used to
embed flash objects in your browsers.

Function call removed from original library. Now it returns only constructor. It was made because swfobject runs some incredebly dull code in the start, which can affect page loading time.
So you can run swfobject initialization when you want to.

The full documentation is available at: 
https://code.google.com/p/swfobject/wiki/documentation

## Installation

This module is intended to be used in browserify and can therefor be installed
using npm:

```
npm install --save swfobject
```

```
import Swfobject from 'swfobject'

let swfobject = Swfobject();
```

## Versioning

This module follows the versioning scheme that the swfobject uses. The major is
the major version used by the swfobject project. The minor version is also used
by the project. So swfobject 2.2 maps to 2.2.x on semver. The patch versions are
used by this library to update browserify releases, fixes and other misc
changes.

## License

Same as the swfobject's license, MIT
