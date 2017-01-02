### Installation

Requires vim compiled with lua. On mac:

```
$ brew install macvim --with-cscope --with-luajit --override-system-vim
```

or install neovim

```sh
$ brew install neovim
```

`git clone git://github.com/renatoelias/vimfiles.git ~/.vim && ~/.vim/setup.sh`

Switched the Ack plugin to use [The Silver Searcher](https://github.com/ggreer/the_silver_searcher)
Install OSX: `brew install the_silver_searcher`
Install Ubuntu: `sudo apt-get install silversearcher-ag`

Uses [fzf](https://github.com/junegunn/fzf) for fuzzy finding
