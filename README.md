# @devtea2027/ipsum-ea-repellendus-fugit <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple list of possible Typed Array names.

## Example

```js
const assert = require('assert');

const names = require('@devtea2027/ipsum-ea-repellendus-fugit');

assert(Array.isArray(names));
assert(names.every(name => (
    typeof name === 'string'
    && typeof globalThis[name] === 'function'
    && globalThis[name].name === name
)));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@devtea2027/ipsum-ea-repellendus-fugit
[npm-version-svg]: https://versionbadg.es/ljharb/@devtea2027/ipsum-ea-repellendus-fugit.svg
[deps-svg]: https://david-dm.org/ljharb/@devtea2027/ipsum-ea-repellendus-fugit.svg
[deps-url]: https://david-dm.org/ljharb/@devtea2027/ipsum-ea-repellendus-fugit
[dev-deps-svg]: https://david-dm.org/ljharb/@devtea2027/ipsum-ea-repellendus-fugit/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@devtea2027/ipsum-ea-repellendus-fugit#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@devtea2027/ipsum-ea-repellendus-fugit.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@devtea2027/ipsum-ea-repellendus-fugit.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@devtea2027/ipsum-ea-repellendus-fugit.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@devtea2027/ipsum-ea-repellendus-fugit
[codecov-image]: https://codecov.io/gh/ljharb/@devtea2027/ipsum-ea-repellendus-fugit/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@devtea2027/ipsum-ea-repellendus-fugit/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@devtea2027/ipsum-ea-repellendus-fugit
[actions-url]: https://github.com/devtea2027/ipsum-ea-repellendus-fugit/actions
