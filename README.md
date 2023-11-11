# My personal dotfiles

## Chezmoi

I manage my dotfiles with [git](https://git-scm.com/) and [chezmoi](https://www.chezmoi.io/) .
For a short introduction to chezmoi visit their [Quick start guide](https://www.chezmoi.io/quick-start/).
chezmoi saves the config files in a local git repository in `~/.local/share/chezmoi`.
You can clone this repository there and then apply my entire setup with `chezmoi apply`, if you desire.

Alternatively, this can be done with a single command:

```{bash}
chezmoi init --apply https://github.com/mkaltw/dotfiles.git
```

---

## Alacritty

Pretty much the default config.
I currently use the `JetBrains Mono` font, but alternate between `Fira Code`, `Cascadia Code` and `Hack` as well.
There is also a simple keymap to toggle fullscreen mode with `F11`.

## bash

Simple `.bashrc` files with a bunch of *aliases* using handy little tools written in Rust.
You can check these out at [rust-unofficial/awesome-rust](https://github.com/rust-unofficial/awesome-rust).

Once I get around to it I will switch to `zsh` and add a `.zshrc` to this repository.

## starship

I am using the starship prompt with their *Nerd Font Symbols Preset*.

## Catppuccin

Pretty much my entire setup uses the *Catppuccin-Mocha* theme by [Catppuccin](https://github.com/catppuccin). 

## tmux

Shamelessly stolen from the [Dreams of Code](https://www.youtube.com/@dreamsofcode) tmux setup [video](https://youtu.be/DzNmUNvnB04) and customized a little.

## Neovim

I started out with [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim) and have not made a lot of changes so far.

Notably, I prefer having all whitespace characters displayed in my text editor.
This can be toggled with `:set nolist` and `:set list` respectively.

