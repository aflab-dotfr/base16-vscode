# base16-vscode

Generate vscode json theme file.

## Installation

To activate your vscode theme, you can use this basic extension.

Copy the extension files inside the vscode folder.

```
$ cp extension ~/vscode-oss/extensions/base16-theme
```

Enable the extension inside the extensions tab (CTRL+SHIFT+X).

Copy your generated theme json file inside with the name `base16-theme.json`.

```
$ cp output/vscode/themes/base16-morio.json cp ~/vscode-oss/extensions/base16-theme/base16-theme.json
```

Restart vscode then activate your theme by pressing CTRL+K CTRL+T and search for Base16 Theme.

You can update your theme simply by replacing the base16-theme.json.