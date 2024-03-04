# ESLint Configuration for React with TypeScript

This is a [ESLint](https://eslint.org) configuration that is used by the [configs](https://github.com/User0k/configs) repository.
It requires `eslint`, `eslint-plugin-react`, `eslint-plugin-react-hooks`, `@typescript-eslint/parser`, `typescript-eslint/eslint-plugin`, `prettier`,    `eslint-plugin-prettier`.

## Purpose

This approach simplifies ESLint setup for React projects, making it easy to install and use common rules and best practices.

## Installation

To install this ESLint configuration package, use this command:
```npm install -D @user0k/eslint-config-react-ts```

## Usage

After installing the package, you can extend the configuration in your project's `.eslintrc.cjs` file:
```js
module.exports = {
  extends: 'eslint-lite-react-ts/index.js',
  rules: {
  // ... rules you want to override
  },
};
```