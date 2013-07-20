# Configs for environment setup 

Bored of setting up machines for development again and again? It's *tedious*. 
These are some dotfiles that I use very often. If you like [zsh](http://www.zsh.org/), [Vim](http://www.vim.org/), [Solarized](http://ethanschoonover.com/solarized) and [tmux](http://tmux.sourceforge.net/), just run 
(prerequisites: curl, git, vim, zsh)

```shell
curl https://raw.github.com/ChengLong/configs/master/setup.sh | zsh
```

It will:
* Install [Pathogen](https://github.com/tpope/vim-pathogen) if necessary
* Install [Vim solarized](https://github.com/altercation/vim-colors-solarized)
* Install [Nerdtree](https://github.com/scrooloose/nerdtree) for vim
* Copy my [.vimrc](https://raw.github.com/ChengLong/configs/master/.vimrc) to your .vimrc
* Copy my [.zsh_aliases](https://raw.github.com/ChengLong/configs/master/.zsh_aliases) to your .zsh_aliases
* Copy my [.zshrc](https://raw.github.com/ChengLong/configs/master/.zshrc) to your .zshrc
* Copy my [pygmalion.zsh-theme](https://raw.github.com/ChengLong/configs/master/pygmalion.zsh-theme) to your pygmalion.zsh-theme
* Copy my [.tmux.conf](https://raw.github.com/ChengLong/configs/master/.tmux.conf) to your .tmux.conf

## Screenshots

### Vim
![vim](/images/vim.png)

### Zsh prompt
![zsh](/images/zsh.png)

### Nerdtree
![nerdtree](/images/nerdtree.png)
