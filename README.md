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

| Code Name         | Name                  | Description                                                                               | Link                                                    |
| ----------------- | --------------------- | ----------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| `colorswitcher`   | Color Switcher        | Easily cycle through color schemes using keyboard shortcuts or commands.                  | https://github.com/akikareha/micro-colorswitcher-plugin |
| `fmtonsave`       | Format on Save        | Auto-format files on save using formatters like StyLua.                                   | https://github.com/akikareha/micro-fmtonsave-plugin     |
| `autotheme`       | Auto Theme            | Automatically sets the colorscheme based on syntax (filetype).                            | https://github.com/akikareha/micro-autotheme-plugin     |
| `colorshuffle`    | Color Shuffle         | Shuffles your theme each time you open a file.                                            | https://github.com/akikareha/micro-colorshuffle-plugin  |
| `karehacolors`    | Kareha Colors         | A warm and calm color scheme, evoking the feel of fallen leaves.                          | https://github.com/akikareha/micro-kareha-colorschemes  |
| `diffpatchsyntax` | diff and patch Syntax | Syntax highlighting for diff and patch files.                                             | https://github.com/akikareha/micro-diffpatch-syntax     |
| `gtypistsyntax`   | GNU Typist Syntax     | Syntax highlighting for GNU Typist lesson files.                                          | https://github.com/akikareha/micro-gtypist-syntax       |
| `mdfy`            | MDfy (Markdown-ize)   | Convert a URL under the cursor into a Markdown link.                                      | https://github.com/akikareha/micro-mdfy-plugin          |
| `toggle`          | Toggle Options        | Adds two commands for toggling boolean configuration options.                             | https://github.com/akikareha/micro-toggle-plugin        |
| `shout`           | Shell Out             | Run the current line as a shell command and insert the output below.                      | https://github.com/akikareha/micro-shout-plugin         |
| `openconfig`      | Open Config           | Adds commands to open micro config files like settings.json, bindings.json, and init.lua. | https://github.com/akikareha/micro-openconfig-plugin    |
