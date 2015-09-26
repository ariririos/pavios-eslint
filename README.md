# Pavios-Eslint

This is the "eslint" task for use with [Pavios](https://npmjs.org/package/pavios).

## Installation

```
npm install --save-dev pavios pavios-eslint
```

## Use

See the [config guide](https://github.com/rioc0719/pavios#config-guide) for information on how to use this package.

### Configuration

This task accepts two configuration options:

- `files: [String]`: An array of strings (fileglobs) that will be linted with [eslint](https://npmjs.org/package/eslint).
- `linterOpts: Object`: An object that will be passed directly to [eslint](https://npmjs.org/package/eslint).
