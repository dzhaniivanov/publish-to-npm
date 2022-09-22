# publish-to-npm

[![npm (scoped) ](https://img.shields.io/github/issues/dzhaniivanov94/publish-to-npm)(https://www.npmjs.com/package/@d_ivanov/tiny)]

Removes all spaces from a string.

## Install

```
$npm install @d_ivanov/tiny
```

## Usage

```js
const tiny = require("@d_ivanov/tiny");
tiny("So much space");
//=> "Somuchspace!"

tiny(2352);
//=>Uncaught TypeError:Tiny wants a string!
```
