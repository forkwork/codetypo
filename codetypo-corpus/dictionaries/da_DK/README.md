# CodeTypo Danish Dictionary

Danish dictionary for CodeTypo.

This is a pre-built dictionary, base on [Stavekontrolden](https://www.stavekontrolden.dk), for use with CodeTypo.

## Installation

Global Install and add to CodeTypo global settings.

```sh
npm install -g @codetypo/dict-da-dk
codetypo link add @codetypo/dict-da-dk
```

## Uninstall from CodeTypo

```sh
codetypo link remove @codetypo/dict-da-dk
```

## Manual Installation

The `codetypo-ext.json` file in this package should be added to the import section in your `codetypo.json` file.

```javascript
{
    // …
    "import": ["@codetypo/dict-da-dk/codetypo-ext.json"],
    "language": "da-DK",
    // …
}
```

## Resources

The Hunspell source for this dictionary can be found:

- https://github.com/wooorm/dictionaries/tree/main#readme

<!--- codetypo:ignore Stavekontrolden --->
