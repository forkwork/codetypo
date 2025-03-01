# CodeTypo Svelte Dictionary

Svelte dictionary for codetypo.

This is a pre-built dictionary for use with CodeTypo.

## Installation

Global Install and add to CodeTypo global settings.

```sh
npm install -g @codetypo/dict-svelte
codetypo link add @codetypo/dict-svelte
```

## Uninstall from CodeTypo

```sh
codetypo link remove @codetypo/dict-svelte
```

## Manual Installation

Manual installation is useful if you want to include this dictionary as part of your CI/CD lint process.

```
npm i @codetypo/dict-svelte
```

The `codetypo-ext.json` file in this package should be added to the import section in your `codetypo.json` file.

```javascript
{
    // …
    "import": ["@codetypo/dict-svelte/codetypo-ext.json"],
    // …
}
```

# Dictionary Development

See: [How to Create a New Dictionary](https://github.com/khulnasoft/codetypo-dicts#how-to-create-a-new-dictionary)

## License

MIT

> Some packages may have other licenses included.
