# Library Starter Kit

Library starter kit using Webpack.

* ES6 Source
* Exports [UMD](https://github.com/umdjs/umd) format
* Compiles JavaScript down to ES5 and is minified

## Instructions

### Configure Library

1. Inside webpack.config.js change the name of the library: `libraryName: '...'`
2. Inside package.json change the file name of the main property: `"main": "src/..."`

### Compile Library

1. Install dependencies: `npm install`
1. Run production / development environment
  * For production: `npm run compile`
  * For development: `npm run watch`

#### Production

JavaScript compiles down to ES5 and is minified.

#### Development

Watches and compiles JavaScript.

## Licence

Licensed under the [MIT](https://opensource.org/licenses/MIT) Licence.
