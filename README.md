# @taktikorg/dolorum-quasi <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@taktikorg/dolorum-quasi');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@taktikorg/dolorum-quasi
[npm-version-svg]: https://versionbadg.es/inspect-js/@taktikorg/dolorum-quasi.svg
[deps-svg]: https://david-dm.org/inspect-js/@taktikorg/dolorum-quasi.svg
[deps-url]: https://david-dm.org/inspect-js/@taktikorg/dolorum-quasi
[dev-deps-svg]: https://david-dm.org/inspect-js/@taktikorg/dolorum-quasi/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@taktikorg/dolorum-quasi#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@taktikorg/dolorum-quasi.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@taktikorg/dolorum-quasi.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@taktikorg/dolorum-quasi.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@taktikorg/dolorum-quasi
[codecov-image]: https://codecov.io/gh/inspect-js/@taktikorg/dolorum-quasi/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@taktikorg/dolorum-quasi/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@taktikorg/dolorum-quasi
[actions-url]: https://github.com/taktikorg/dolorum-quasi/actions
