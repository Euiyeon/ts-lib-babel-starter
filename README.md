# ts-domlib-starter

[![CircleCI](https://circleci.com/gh/Euiyeon/ts-domlib-starter.svg?style=svg)](https://circleci.com/gh/Euiyeon/ts-domlib-starter)
[![codecov](https://codecov.io/gh/Euiyeon//ts-domlib-starter/branch/master/graph/badge.svg)](https://codecov.io/gh/Euiyeon//ts-domlib-starter)
[![Known Vulnerabilities](https://snyk.io//test/github/Euiyeon//ts-domlib-starter/badge.svg?targetFile=package.json)](https://snyk.io//test/github/Euiyeon//ts-domlib-starter?targetFile=package.json)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Typescript-based JavaScript DOM library starter package

based on <https://github.com/bitjson/typescript-starter>

[![js-standard-style](https://cdn.rawgit.com/standard/standard/master/badge.svg)](http://standardjs.com)

## Resource

* [API Document](https://euiyeon.github.io/ts-domlib-starter/)

### Continuous integration

* [CircleCI](https://circleci.com) - Continuous Integration and Delivery
* [codecov](https://codecov.io) - leading, dedicated code coverage
* [snyk.io](https://snyk.io) - Continuously find and fix vulnerabilities for npm
* [Codacy](https://www.codacy.com) - Automated code reviews & code analytics

## Build

```sh
yarn build
```
or
```sh
gulp build
```

### Output

```plain
├── dist        -- UMD, minified
├── build
|  ├── main     -- Common JS
|  ├── module   -- ES Modules
```

### Gulp Build Tasks

#### Common JS

* name: `build:cjs`
* dest: `build/main/**`

#### ES Modules

* name: `build:esm`
* dest: `build/module/**`

#### UMD(Universal Module Definition)

dependent gulp tasks: `build:esm`

* name: `build:umd`
* dest: `dist/**`

## Test

```sh
yarn test
```

### Coverage Check

```sh
yarn cov:check
```

## TODO
* [ ] ..
    
## License

MIT. See [LICENSE](./LICENSE) for details.
