General-purpose eslint linting
==============================

[![npm version](https://img.shields.io/npm/v/stb-eslint.svg?style=flat-square)](https://www.npmjs.com/package/stb-eslint)
[![dependencies status](https://img.shields.io/david/stbsdk/eslint.svg?style=flat-square)](https://david-dm.org/stbsdk/eslint)
[![devDependencies status](https://img.shields.io/david/dev/stbsdk/eslint.svg?style=flat-square)](https://david-dm.org/stbsdk/eslint?type=dev)
[![Gitter](https://img.shields.io/badge/gitter-join%20chat-blue.svg?style=flat-square)](https://gitter.im/DarkPark/stbsdk)


## Installation ##

```bash
npm install stb-eslint
```


## Usage ##

Add file `.eslintrc.js` to your project with the following content:

```js
module.exports = {
    extends: require.resolve('stb-eslint')
};
```

Run linting for your project:

```bash
npx eslint .
```


## Contribution ##

If you have any problems or suggestions please open an [issue](https://github.com/stbsdk/eslint/issues)
according to the contribution [rules](.github/contributing.md).


## License ##

`stb-eslint` is released under the [MIT License](license.md).
