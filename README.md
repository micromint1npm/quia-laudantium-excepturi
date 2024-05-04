# @micromint1npm/quia-laudantium-excepturi <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@micromint1npm/quia-laudantium-excepturi');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@micromint1npm/quia-laudantium-excepturi
[npm-version-svg]: https://versionbadg.es/inspect-js/@micromint1npm/quia-laudantium-excepturi.svg
[deps-svg]: https://david-dm.org/inspect-js/@micromint1npm/quia-laudantium-excepturi.svg
[deps-url]: https://david-dm.org/inspect-js/@micromint1npm/quia-laudantium-excepturi
[dev-deps-svg]: https://david-dm.org/inspect-js/@micromint1npm/quia-laudantium-excepturi/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@micromint1npm/quia-laudantium-excepturi#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@micromint1npm/quia-laudantium-excepturi.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@micromint1npm/quia-laudantium-excepturi.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@micromint1npm/quia-laudantium-excepturi.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@micromint1npm/quia-laudantium-excepturi
[codecov-image]: https://codecov.io/gh/inspect-js/@micromint1npm/quia-laudantium-excepturi/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@micromint1npm/quia-laudantium-excepturi/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@micromint1npm/quia-laudantium-excepturi
[actions-url]: https://github.com/micromint1npm/quia-laudantium-excepturi/actions
