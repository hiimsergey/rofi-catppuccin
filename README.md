# Catppuccin Rofi theme
A simple theme for [rofi](https://github.com/davatorium/rofi) based on the [Catppuccin](https://catppuccin.com) theme.

![screenshot](rofi_catppuccin_screenshot.png)

## Installation
1. Copy [`catppuccin-lavrent-mocha.rasi`](https://github.com/hiimsergey/rofi-catppuccin/blob/mocha/gruvbox-material.rasi) to `~/.config/rofi/`
2. Add the following lines to your config (`~/.config/rofi/config.rasi`):

```
configuration {
    show-icons: true;

    display-ssh:    "󰣀 ssh:";
    display-run:    "󱓞 run:";
    display-drun:   "󰣖 drun:";
    display-window: "󱂬 window:";
    display-combi:  "󰕘 combi:";
    display-filebrowser: "󰉋 filebrowser:";
}

@theme "~/.config/rofi/catppuccin-lavrent-mocha.rasi"
```