### [lazydocker](https://github.com/jesseduffield/lazydocker)

#### Install using Git

If you are a Git user, you can install the theme and keep it up to date by cloning the repo:

```bash
git clone https://github.com/lfreixial/lazydocker.git
```

#### Install manually

Download using the [GitHub `.zip` download](https://github.com/lfreixial/lazydocker/archive/main.zip) option and unzip it.

#### Activating theme

1. Open lazydocker's configuration file by selecting the Status panel and pressing `e`. On Linux, it is usually `~/.config/lazydocker/config.yml` (or `$XDG_CONFIG_HOME/lazydocker/config.yml` when set).
2. Copy the `gui.theme` block from [`config/dracula.yml`](./config/dracula.yml) into your configuration. If you already have a `gui:` section, merge `theme:` into it; keep your other settings and avoid duplicate `gui:` or `theme:` keys. For an empty configuration, copy the entire file.
3. Restart `lazydocker`.

For the matching background, foreground, and ANSI colors, also use a [Dracula theme for your terminal](https://draculatheme.com/). Lazydocker inherits these colors from the terminal; its `gui.theme` controls the borders, selected row, and options text.
