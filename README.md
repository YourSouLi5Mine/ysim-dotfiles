# ysim dotfiles :sunglasses:
by: (Jorge Precich)
compatibility: Linux

### Requirements

The installation will overwrite existing dotfiles in your $HOME and `.dotfiles, .vim` directories.

## How to install

```
curl -L https://raw.github.com/YourSouLi5Mine/ysim-dotfiles/master/bin/dotfiles | bash
```

### After installation

The first time opening nvim you have to use: `:PlugInstall` to install all the plugins, then: `:source ~/.vimrc`

To get all tmux plugins to work run: `<C-B>U` and type `all` to update all the plugins.

Further information: [TPM](https://github.com/tmux-plugins/tpm)

## How to update

`dotfiles`

## Features

### zsh

* [Prezto :green_heart:](https://github.com/sorin-ionescu/prezto)

### tmux

### nvim

### Packages

### Snaps

### Shortcuts & Commands

[Aliases](/shell/shell_aliases)
[Zprezto](https://github.com/sorin-ionescu/prezto/tree/master/modules)
Here are the prezto shortcuts I'm using:

## Scripts

### If already downloaded the dotfiles

```
osxdefaults
background url image_name
screensaver url image_name
install_nvm
install_rvm
```

### If not

```
curl -L https://raw.github.com/YourSouLi5Mine/ysim-dotfiles/master/bin/osxdefaults | bash
curl -L https://raw.github.com/YourSouLi5Mine/ysim-dotfiles/master/bin/background | bash -s url image_name
curl -L https://raw.github.com/YourSouLi5Mine/ysim-dotfiles/master/bin/screensaver | bash -s url image_name
curl -L https://raw.github.com/YourSouLi5Mine/ysim-dotfiles/master/bin/install_nvm | bash
curl -L https://raw.github.com/YourSouLi5Mine/ysim-dotfiles/master/bin/install_rvm | bash
```
### WYSIWYG

![nvim](/files/nvim.png)
