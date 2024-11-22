# s-utils-llm

<a href="https://github.com/SebastianWesolowski/starter-npm-package"><img align="left" width="440" height="180" alt="s-utils-llm package" src="srcReadme/heroImageReposytory.png"></a>

## Important Links

- [![npm package][npm-img]][npm-url]
- [![Build Status][build-img]][build-url]
- [Author page](PLACEHOLDER_PAGE_AUTHOR)

<br>

---

<br/>

s-utils-llm is utils for working with LLM models

## Install

```bash
npm install s-utils-llm
```

## Usage

```ts
import { myPackage } from 's-utils-llm';

// Default value is 'Watermelon 🍉'
getFavoriteFruit();
//=> 'My favorite fruit is Watermelon 🍉'

getFavoriteFruit('Apple 🍎');
//=> 'My favorite fruit is Apple 🍎'
```

## API

### getFavoriteFruit(fruit?)

Returns a string with your favorite fruit.

#### fruit

Type: `string`
Default: `'Watermelon 🍉'`

The fruit to use in the returned string. Must be a string value.

#### Returns

Type: `string`

Returns a string in the format: `'My favorite fruit is {fruit}'`

#### Throws

Throws an error if the fruit parameter is not a string.

#### Example

Lorem ipsum.

## Badges

[![Downloads][downloads-img]][downloads-url]
[![Issues][issues-img]][issues-url]
[![Commitizen Friendly][commitizen-img]][commitizen-url]
[![Semantic Release][semantic-release-img]][semantic-release-url]

[build-img]: https://github.com/SebastianWesolowski/s-utils-llm/actions/workflows/release.yml/badge.svg
[build-url]: https://github.com/SebastianWesolowski/s-utils-llm/actions/workflows/release.yml
[downloads-img]: https://img.shields.io/npm/dt/s-utils-llm
[downloads-url]: https://www.npmtrends.com/s-utils-llm
[npm-img]: https://img.shields.io/npm/v/s-utils-llm
[npm-url]: https://www.npmjs.com/package/s-utils-llm
[issues-img]: https://img.shields.io/github/issues/SebastianWesolowski/s-utils-llm
[issues-url]: https://github.com/SebastianWesolowski/s-utils-llm/issues
[semantic-release-img]: https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg
[semantic-release-url]: https://github.com/semantic-release/semantic-release
[commitizen-img]: https://img.shields.io/badge/commitizen-friendly-brightgreen.svg
[commitizen-url]: http://commitizen.github.io/cz-cli/
