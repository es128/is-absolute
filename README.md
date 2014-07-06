# is-absolute [![NPM version](https://badge.fury.io/js/is-absolute.png)](http://badge.fury.io/js/is-absolute)

> Return true if a file path is absolute.

Based on the `isAbsolute` utility method in [express](https://github.com/visionmedia/express).

## Install
Install with [npm](npmjs.org):

```bash
npm i is-absolute --save-dev
```

## Usage

```js
var isAbsolute = require('is-absolute');
console.log(isAbsolute('abc'));
//=> ['a', 'b', 'c'];
```

## API

**Example:**

```js
isAbsolute('a/b/c.js');
//=> 'false'

isAbsolute('C://a/b/c.js');
//=> 'true'
```

* `filepath` {String}  
* `return` {Boolean}

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2014 Jon Schlinkert, contributors.  
Released under the MIT license

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on July 06, 2014._