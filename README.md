use your base16 [tinted-theme](https://github.com/tinted-theming/home) theme with [tridactyl](https://github.com/tridactyl/tridactyl) 
# Basic Usage Instructions

Add the following toml settings to your Tinty ~/.config/tinted-theming/tinty/config.toml file:
```toml
[[items]]
name = "tridactyl"
path = "https://github.com/rwendell/tinted-tridactyl"
themes-dir = "themes"
hook = "command cp -f %f ~/.config/tridactyl/themes/colors.css"
supported-systems = ["base16"]
```
you can then apply with `<cmd>colorscheme colors<cr>`

