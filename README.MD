# [@murshidazher/prettier-config](https://github.com/murshidazher/prettier-config) [![npm](https://img.shields.io/npm/v/prettier-config.svg?label=&color=0080FF)](https://github.com/murshidazher/prettier-config/releases/latest)

![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)

> An opinionated prettier configuration to make linting a 🌬️. **Accepting PRs**

Quickly format your JavaScript files with this easy to install and use Prettier configuration.

## Table of Contents

- [Table of Contents](#table-of-contents)
  - [Purpose](#purpose)
  - [Installation](#installation)
  - [How to use](#how-to-use)
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
"prettier": "@murshidazhers/prettier-config"
```

Under script objects

```sh
"format": "prettier --write \"{,!(node_modules)/**/}*.js\""
```

## Contributing

How to [contribute](/CONTRIBUTING.MD) to this open source library

## License

Copyright © 2020-2021 [Murshid Azher](https://murshidazher.com). This library is licensed under the MIT [license](./LICENCE).
