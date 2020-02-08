# ysim dotfiles
By Jorge Precich

For Ubuntu 18.04

## How to install

Your old `.zshrc`, `.vimrc`, `.tmux_conf`

```
Dotfiles:
curl -L https://raw.github.com/YourSouLi5Mine/ysim-dotfiles/master/bin/dotfiles | bash

General setings:
curl -L https://raw.github.com/YourSouLi5Mine/ysim-dotfiles/master/bin/osxdefaults | bash
```

## Options

```
-h,  --help        Prints the help
-np, --no-packages Suppress packages updates
-ns, --no-sync     Suppress pulling from the remote repository
```

## After installation

The first time opening nvim you have to use: `:PlugInstall` to install all the plugins, then: `:source ~/.vimrc`

[vim-plug](https://github.com/junegunn/vim-plug)

To get all tmux plugins to work run: `<C-B>U` and type `all` to update all the plugins.

[TPM](https://github.com/tmux-plugins/tpm)

## How to update

`dotfiles`

## Packages

```
git zsh oh-my-zsh tmux silversearcher-ag neovim gnom-tweaks autojump google-chrome-stable steam
```

## Snaps

```
slack spotify
```

## Shortcuts & Commands

[Aliases](/shell/shell_aliases)
[Functions](/shell/functions)

## Scripts

```
osxdefaults
background url image_name
screensaver url image_name
install_nvm
install_rvm
```

## Theme

![pure](https://github.com/sindresorhus/pure)

## WYSIWYG

![nvim](/files/nvim.png)
![terminal](/files/terminal.png)
