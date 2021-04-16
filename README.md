# base16-vscode

Generate vscode json theme file.

## Installation

To activate your vscode theme, you can use this basic extension.

Copy the extension folder inside the vscode folder.

```
$ cp templates/vscode/extension ~/vscode-oss/extensions/base16-theme
```

Enable the extension inside the extensions tab <kbd>CTRL+SHIFT+X</kbd>.

Copy your generated theme json file inside with the name `base16-theme.json`.

```
$ cp output/vscode/themes/base16-morio.json ~/vscode-oss/extensions/base16-theme/base16-theme.json
```

Restart vscode then activate your theme by pressing <kbd>CTRL+K</kbd> <kbd>CTRL+T</kbd> and search for Base16 Theme.

You can update your theme simply by replacing the base16-theme.json.