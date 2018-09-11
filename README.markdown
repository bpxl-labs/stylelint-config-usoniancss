# stylelint-config-usoniancss
[![NPM version](http://img.shields.io/npm/v/stylelint-config-usoniancss.svg)](https://www.npmjs.org/package/stylelint-config-usoniancss) 

> Usonian CSS shareable config for stylelint.

Configuration rules to ensure your CSS code is compliant with UsonianCSS.

## Installation

```console
$ npm install --save-dev stylelint-config-usoniancss
```

## Usage

Set your stylelint config to:

```json
{
  "extends": "stylelint-config-usoniancss"
}
```

### Extending the config

Simply add a `"rules"` key to your config and add your overrides there.

For example, to change the `indentation` to tabs and disable the `color-hex-case` rule:


```json
{
  "extends": "stylelint-config-usoniancss",
  "rules": {
    "indentation": "tab",
    "color-hex-case": null
  }
}
```

## License

MIT © [Brad Cerasani](http://bradcerasani.me)


---

Website: [blackpixel.com](https://blackpixel.com) &nbsp;&middot;&nbsp;
GitHub: [@bpxl-labs](https://github.com/bpxl-labs/) &nbsp;&middot;&nbsp;
Twitter: [@blackpixel](https://twitter.com/blackpixel) &nbsp;&middot;&nbsp;
Medium: [@bpxl-craft](https://medium.com/bpxl-craft)
