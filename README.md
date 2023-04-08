# setuper

CLI application to automatize an enviroment setup, wich includes
customize the theme, colors, terminal, programs and dotfiles.

Created to setup [my dotfiles](https://github.com/iagotito/dotfiles)
into an Ubuntu enviroment, but I could evolve to be more flexible...
I will probably never do this though.

Based on [Build a Custom CLI with
Bash](https://medium.com/@brotandgames/build-a-custom-cli-with-bash-e3ce60cfb9a4)

## How to use

To install and configure dotfiles for everything (zsh, tmux, themes etc) run:

```shell
./setuper zsh all
./setuper neovim all
./setuper terminal all
./setuper system all

# or

./setuper all
```

To read what action do, check the docs:

```
./setuper help

./setuper [option] help
```
