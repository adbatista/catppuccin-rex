# Catppuccin for Rex

[Catppuccin](https://github.com/catppuccin/catppuccin) themes for the [Rex](https://www.superlogical.com/rex/docs) terminal.

| Theme | Appearance |
|---|---|
| `Catppuccin Latte` | light |
| `Catppuccin Frappé` | dark |
| `Catppuccin Macchiato` | dark |
| `Catppuccin Mocha` | dark |

The files use the Ghostty theme format, which Rex.app can import. The colors come straight from the official [catppuccin/kitty](https://github.com/catppuccin/kitty) themes.

## Install

1. Clone this repository.
2. In Rex.app, open the command palette and run **Import Theme File**. Pick one of the theme files. Repeat for each flavor you want.
3. Run **Change Theme…** to switch between them, or choose a theme for light and dark appearance in Settings → Themes.

A nice setup is Latte as the light theme and Mocha as the dark theme, with Color Scheme set to auto so Rex follows the system appearance.

With Remote Control turned on in Rex.app, you can also import a theme from the command line:

```sh
rex do client.theme.import path="$PWD/Catppuccin Mocha"
```

## Credits

The color values come from [catppuccin/kitty](https://github.com/catppuccin/kitty), which is MIT licensed, Copyright (c) 2021 Catppuccin.
