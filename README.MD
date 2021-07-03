# [@murshidazher/prettier-config](https://github.com/murshidazher/prettier-config) [![npm](https://img.shields.io/npm/v/@murshidazher/prettier-config.svg?label=&color=0080FF)](https://github.com/murshidazher/prettier-config/releases/latest)

![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)

> An opinionated prettier configuration to make linting a 🌬️. **Accepting PRs**

Quickly format your JavaScript files with this easy to install and use Prettier configuration.

## Table of Contents

- [Table of Contents](#table-of-contents)
  - [Purpose](#purpose)
  - [Installation](#installation)
  - [How to use](#how-to-use)
  - [Contributors](#contributors)
  - [Contributing](#contributing)
  - [License](#license)

## Purpose

[prettier](https://prettier.io/) is an opinionated code formatter easy to configure and integrate with Code Editors. This configuration aims to quickly install and config JavaScript projects for consistent code style standards.

This package can be used as a stand-alone config or integrated with any linter.

## Installation

```sh
npm install -D prettier @murshidazher/prettier-config
```

If you use yarn as the package manager,

```sh
yarn add -D prettier @murshidazher/prettier-config
```

## How to use

In your `package.json` add:

```sh
"prettier": "@murshidazher/prettier-config"
```

Under script objects

```sh
"format": "prettier --write \"{,!(node_modules)/**/}*.js\""
```

## Extending

This configuration is not intended to be changed, but if you have a setup where modification is required, it is possible. Prettier does not offer an "extends" mechanism as you might be familiar from tools such as ESLint.

To extend a configuration you will need to create either `.prettierrc.js` or `prettier.config.js` file:

```js
// .prettierrc.js
module.exports = {
    ...require('@murshidazher/prettier-config'),
    semi: false
    // more configuration options goes here!
};
```

## Contributors

[![contributors](https://contrib.rocks/image?repo=murshidazher/prettier-config)](https://github.com/murshidazher/prettier-config/graphs/contributors)

## Contributing

How to [contribute](/CONTRIBUTING.MD) to this open source library

## License

Copyright © 2020-2021 [Murshid Azher](https://murshidazher.com). This library is licensed under the [MIT](./LICENCE).
