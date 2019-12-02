[![Actions Status](https://github.com/reireias/nodejs-template/workflows/main/badge.svg)](https://github.com/reireias/nodejs-template/actions) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# nodejs-template
My Node.js project template for GitHub template repository.

## Environment

This template project uses the following environments.

- Node.js 12.x
- Yarn

## Features

### ESLint
[ESLint](https://eslint.org/) is a lint tool for JavaScript.

The following settings are written in `.eslintrc.js` file.

- Use ECMAScript 2018
- Use with Prettier

### Prettier
[Prettier](https://prettier.io/) is a defact standard JavaScript code formatter tool.

The following settings are written in `.prettierrc` file.

- No semicolon
- Use single quote for string

### GitHub Actions
This template project uses [GitHub Actions](https://help.github.com/en/actions) for CI.

Settings to execute ESLint are defined in `.github/workflows/main.yml`.

### Commitizen
[Commitizen](http://commitizen.github.io/cz-cli/) is simple commit conventions for internet citizens.

You can commit with commitizen rule at `yarn commit` command.

### EditorConfig
[EditorConfig](https://editorconfig.org/) helps maintain consistent coding styles for multiple developers working on the same project across various editors and IDEs.

My favorite configs are written in `.editorconfig` file.
