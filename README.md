# Aki Kareha's Unofficial Plugin Channel for Micro

This is an unofficial plugin channel for the
[micro](https://micro-editor.github.io/) text editor.
By adding this channel to your plugin sources, you can easily install several
unofficial plugins developed by [Aki Kareha](https://github.com/akikareha).

## Installation

To add this plugin channel, edit your `settings.json` file while preserving
proper JSON format.
This file is typically located at `~/.config/micro/settings.json`.

Add (or append) the following to the `"pluginchannels"` list:

```json
{
    "pluginchannels": [
        "https://raw.githubusercontent.com/micro-editor/plugin-channel/master/channel.json",
        "https://raw.githubusercontent.com/akikareha/micro-unofficial-plugin-channel/master/channel.json"
    ]
}
```

To install a plugin from this channel (for example, `colorswitcher`), open
`micro` and run:

```
plugin install colorswitcher
```

## Plugins

| Code Name         | Name                  | Description                                                                    | Link                                                    |
| ----------------- | --------------------- | ------------------------------------------------------------------------------ | ------------------------------------------------------- |
| `colorswitcher`   | Color Switcher        | Easily cycle through micro color schemes using keyboard shortcuts or commands. | https://github.com/akikareha/micro-colorswitcher-plugin |
| `fmtonsave`       | Format on Save        | Auto-format files on save in micro using formatters like StyLua.               | https://github.com/akikareha/micro-fmtonsave-plugin     |
| `autotheme`       | Auto Theme            | Automatically sets the colorscheme of micro based on syntax (filetype).        | https://github.com/akikareha/micro-autotheme-plugin     |
| `colorshuffle`    | Color Shuffle         | A micro plugin that shuffles your theme each time you open a file.             | https://github.com/akikareha/micro-colorshuffle-plugin  |
| `karehacolors`    | Kareha Colors         | A warm and calm color scheme for micro, evoking the feel of fallen leaves.     | https://github.com/akikareha/micro-kareha-colorschemes  |
| `diffpatchsyntax` | diff and patch Syntax | Provides syntax highlighting for diff and patch files in micro.                | https://github.com/akikareha/micro-diffpatch-syntax     |
