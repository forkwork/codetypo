# CodeTypo Persian Dictionary

Persian dictionary for codetypo.

This is a pre-built dictionary for use with codetypo.

## Installation

Global Install and add to codetypo global settings.

```sh
npm install -g @codetypo/dict-fa-ir
codetypo link add @codetypo/dict-fa-ir
```

## Uninstall from codetypo

```sh
codetypo link remove @codetypo/dict-fa-ir
```

## Manual Installation

The `codetypo-ext.json` file in this package should be added to the import section in your codetypo.json file.

```javascript
{
    // …
    "import": ["@codetypo/dict-fa-ir/codetypo-ext.json"],
    // …
}
```

## Building

Building is only necessary if you want to modify the contents of the dictionary. Note: Building will take a few minutes for large files.

```sh
npm run build
```

## Resources

The Hunspell source for this dictionary can be found:

- https://github.com/b00f/lilak

## License

Apache 2.0

> Some packages may have other licenses included.
