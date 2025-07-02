# Tokyo Night for Rofi

A modern, visually pleasing Rofi theme inspired by the [Tokyo Night Neovim theme](https://github.com/folke/tokyonight.nvim). Designed for users who love an elegant, dark UI with soft contrast and vibrant highlights, this theme pairs beautifully with terminals using the [Tokyo Night color palette](https://github.com/davidmathers/tokyo-night-kitty-theme), including Kitty, Alacritty, and WezTerm.

---

## Features

- Fully themed Rofi interface (drun, run, window, etc.)
- Tokyo Night colors (`#1a1b26`, `#c0caf5`, `#7aa2f7`, etc.)
- Clean, minimal style with consistent spacing and alignment
- Highlights for selected/hovered entries
- Works seamlessly with Nerd Fonts and common icon themes

---

## Installation

### Quick Install

```bash
# Create the Rofi themes directory
mkdir -p ~/.config/rofi/themes/

# Download the theme file
curl -L -o ~/.config/rofi/themes/tokyonight.rasi https://raw.githubusercontent.com/lairizzle/rofi-tokyonight/master/tokyonight.rasi

# Launch rofi using the theme
rofi -show drun -theme tokyonight
```

