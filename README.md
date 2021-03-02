# @jupi/tiny

Removes all spaces from a string.

## Install

```
$ npm install @jupi/tiny
```

## Usage

```js
const spacekiller = require("@jupi/tiny");

spacekiller("So much space!");
//=> "Somuchspace!"

spacekiller(1337);
//=> Uncaught TypeError: spacekiller wants a string!
//    at spacekiller (<anonymous>:2:41)
//    at <anonymous>:1:1
```