# Catppuccin Rofi theme
A simple theme for [rofi](https://github.com/davatorium/rofi) based on the [Catppuccin](https://catppuccin.com) theme.

![rofi_catppuccin_screenshot](https://github.com/hiimsergey/rofi-catppuccin/assets/91432388/06e6bdfb-7936-4204-9f05-9bbb866c8529)

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
