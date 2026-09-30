### [lazydocker](https://github.com/jesseduffield/lazydocker)

#### Install using Git

If you use Git, clone the repository to install the theme and keep it up to date:

```bash
git clone https://github.com/dracula/lazydocker.git
```

#### Install manually

Download the [GitHub `.zip` archive](https://github.com/dracula/lazydocker/archive/main.zip), then extract it.

#### Activating theme

1. Open lazydocker's configuration file by selecting the Status panel and pressing `e`. On Linux, the file is usually located at `~/.config/lazydocker/config.yml`, or at `$XDG_CONFIG_HOME/lazydocker/config.yml` if `XDG_CONFIG_HOME` is set.
2. Copy the `gui.theme` block from [`config/dracula.yml`](./config/dracula.yml) into your configuration file. If it already contains a `gui:` section, add or replace its `theme:` block while preserving your other settings. Do not create duplicate `gui:` or `theme:` keys. If the configuration file is empty, copy the entire contents of `config/dracula.yml`.
3. Restart `lazydocker`.

For matching background, foreground, and ANSI colors, install a [Dracula theme for your terminal](https://draculatheme.com/?categories=terminal). Lazydocker inherits these colors from your terminal, while its `gui.theme` settings control borders, the selected row, and option text.
