# Kitty Terminal Config

## Setup Guide

[Install Kitty](https://sw.kovidgoyal.net/kitty/)

Clone the contents of this repo into your kitty config directory:
```
git clone git@github.com:Adam-Alj/kitty-conf.git ~/.config/kitty/
```

Grab this theme from kitty-themes:
```
THEME="https://raw.githubusercontent.com/dexpota/kitty-themes/master/themes/Monokai_Pro_(Filter_Octagon).conf"

wget "$THEME" -P ~/.config/kitty/kitty-themes/themes
```

Create a symlink to the theme via:
```
ln -s kitty-themes/themes/Monokai_Pro_\(Filter_Octagon\).conf theme.conf
```

