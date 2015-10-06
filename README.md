# v8is

[![Build Status](https://travis-ci.org/evanlucas/v8is.svg)](https://travis-ci.org/evanlucas/v8is)
[![Coverage Status](https://coveralls.io/repos/evanlucas/v8is/badge.svg?branch=master&service=github)](https://coveralls.io/github/evanlucas/v8is?branch=master)

Type checking on all sorts of values/objects

## Install

```bash
$ npm install v8is
```

## Test

```bash
$ npm test
```

## API

require it using:

```js
const v8is = require('v8is')
```

The following functions are available:

### `isUndefined(arg)`

```js
v8is.isUndefined(undefined) // => true
v8is.isUndefined(null)      // => false
```

### `isNull(arg)`

```js
v8is.isNull(null)      // => true
v8is.isNull(undefined) // => false
```

### `isTrue(arg)`

```js
v8is.isTrue(true)  // => true
v8is.isTrue(false) // => false
```

### `isFalse(arg)`

### `isString(arg)`

### `isSymbol(arg)`

### `isFunction(arg)`

### `isArray(arg)`

### `isObject(arg)`

### `isBoolean(arg)`

### `isNumber(arg)`

### `isInt32(arg)`

### `isUint32(arg)`

### `isDate(arg)`

### `isArgumentsObject(arg)`

### `isBooleanObject(arg)`

### `isNumberObject(arg)`

### `isStringObject(arg)`

### `isRegExp(arg)`

### `isGeneratorFunction(arg)`

### `isGeneratorObject(arg)`

### `isPromise(arg)`

  only works for native promises

### `isMap(arg)`

### `isSet(arg)`

### `isMapIterator(arg)`

### `isSetIterator(arg)`

### `isWeakMap(arg)`

### `isWeakSet(arg)`

### `isArrayBuffer(arg)`

### `isArrayBufferView(arg)`

### `isTypedArray(arg)`

### `isUint8Array(arg)`

### `isInt8Array(arg)`

### `isUint16Array(arg)`

### `isInt16Array(arg)`

### `isUint32Array(arg)`

### `isInt32Array(arg)`

### `isFloat32Array(arg)`

### `isFloat64Array(arg)`

### `isDataView(arg)`

## Author

Evan Lucas

## License

MIT (See `LICENSE` for more info)
