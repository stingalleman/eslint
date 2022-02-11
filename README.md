# Sting's Eslint configs

## Installation

There are four packages available. Each of them can be installed with `yarn add --dev @stingalleman/eslint-config-<name>`.
The following packages can be installed:

```txt
@stingalleman/eslint-base
@stingalleman/eslint-jest
@stingalleman/eslint-typescript
```

You may then extend the installed package(s) in your `.eslintrc.js`, like this:

```js
module.exports = {
  extends: [
    '@stingalleman/base',
    '@stingalleman/jest',
    '@stingalleman/typescript',
  ]
};
```

Feel free to remove any configs you don't need.

## License

This project is licensed under the MIT license.
