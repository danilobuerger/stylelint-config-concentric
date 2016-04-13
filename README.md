# stylelint-config-concentric

Configuration rules based on [stylelint-config-standard](https://github.com/stylelint/stylelint-config-standard) adding a [concentric property sort order](http://rhodesmill.org/brandon/2011/concentric-css/).

Property orders: https://github.com/danilobuerger/stylelint-config-concentric/blob/master/index.js

## Installation

```console
$ npm install stylelint-config-concentric
```

## Usage

Set your stylelint config to:

```json
{
  "extends": "stylelint-config-concentric"
}
```

### Extending the config

Simply add a `"rules"` key to your config and add your overrides there.

For example, to change the `indentation` to tabs and turn off the `number-leading-zero` rule:


```json
{
  "extends": "stylelint-config-concentric",
  "rules": {
    "indentation": "tab",
    "number-leading-zero": null
  }
}
```
