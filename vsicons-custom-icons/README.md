# Primitive File Icons

VSCode does not yet [allow extensions to set default file icons per extension](https://github.com/microsoft/vscode/issues/14662). Until then, `.prim` files will not include a file icon unless you manually enable it:

1. Install [`vscode-icons`](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
2. Find the `vscode-icons` extension in VSCode, click the cog, and select `Set File Icon Theme`.
3. Open your VSCode JSON settings and add the following lines:

```json
{
  // Make sure to update this path:
  "vsicons.customIconFolderPath": "/Users/colin/dev/colinking/primitive-lang",
  "vsicons.associations.files": [
    {
      "icon": "primitive",
      "extensions": ["prim"],
      "light": true,
      "format": "svg"
    }
  ]
}
```

4. Reload your VSCode window.

For more information, see: https://github.com/vscode-icons/vscode-icons/wiki/FineTuning

## Icon Source

`map` icon courtesy of [Tailwind's Heroicons](https://heroicons.com/).
