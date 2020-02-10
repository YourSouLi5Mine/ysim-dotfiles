# ysim dotfiles
By Jorge Precich

For Ubuntu 18.04

## How to install

Your old `.zshrc`, `.vimrc`, `.tmux_conf` will be rename with a suffix `.old`

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

Add to `~/.gitconf` your name and email.

```
[user]
	name  = John Doe
	email = example@gmail.com
```

Download your ssh pub and priv keys to `~/.ssh/id_rsa.pub` and `~/.ssh_id_rsa` respectively.

```
curl -L https://gist.githubusercontent.com/#{your_usename}/#{id_rsa_path} -o ~/.ssh/id_rsa
curl -L https://gist.githubusercontent.com/#{your_usename}/#{id_rsa_pub_path} -o ~/.ssh/id_rsa.pub
chmod 600 ~/.ssh/id_rsa
```

## How to update

`dotfiles`

## Packages

```
curl wget git zsh oh-my-zsh tmux silversearcher-ag neovim gnom-tweaks autojump google-chrome-stable steam sysstat
```

## Snaps

```
slack spotify
```

## Shortcuts & Commands

[Aliases](/shell/aliases)
[Functions](/shell/functions)

## tmux plugins

```
continuum cpu prefix-highlight resurrect sessionist
```

# vim plugins

```
nerdtree
```

# After installing plugins

```
vim -u NONE -c "helptags ~/.vim/plugged/vim-obsession/doc" -c q
```

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
