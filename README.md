# @jupit3r13/tinynpm

Removes all spaces from a string.

## Install

```
$ npm i @jupit3r13/tinynpm
```

## Usage

```js
const tiny = require("@jupit3r13/tinynpm");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: spacekiller wants a string!
//    at spacekiller (<anonymous>:2:41)
//    at <anonymous>:1:1
```
