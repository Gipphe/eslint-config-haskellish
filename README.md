# @gipphe/eslint-config-haskellish

Haskell-like eslint config.

Relies heavily on `sanctuary-style`, with some minor tweaks.

## Usage

First, install:

```shell
npm install --save-dev eslint-config-haskellish
```

or

```shell
yarn add --dev eslint-config-haskellish
```

Then, extend:

`.eslintrc.js`:

```javascript
module.exports = {
  extends: ['haskellish']
};
```
