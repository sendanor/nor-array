[![Build Status](https://secure.travis-ci.org/Sendanor/nor-array.png?branch=master)](http://travis-ci.org/Sendanor/nor-array)

nor-array
=========

Optimized Array Utility Library

Installation
------------

Install using NPM: `npm install nor-array`

forEach()
---------

```
var ARR = require('nor-array');

var a = [1, 2, 3, 4];

ARR(a).forEach(function(v) {
	console.log(v);
});
```

Our implementation is [about 50% faster than the standard `Array.prototype.forEach()`](https://travis-ci.org/sendanor/nor-array/builds/33259661).

License
-------

The MIT style license, see [LICENSE](https://raw.githubusercontent.com/sendanor/nor-array/master/LICENSE).