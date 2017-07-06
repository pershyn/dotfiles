My .dotfiles repository:
=======================

Quick start:
-----------

Fire up terminal and run next commands:

```
# clone dotfiles repository
git clone https://github.com/pershyn/dotfiles.git ~/.dotfiles

# link configs
ln -s ~/.dotfiles/vim ~/.vim
ln -s ~/.vim/vimrc ~/.vimrc
ln -s ~/.dotfiles/tmux.conf ~/.tmux.conf
ln -s ~/.dotfiles/gitignore ~/.gitignore
ln -s ~/.dotfiles/gitconfig ~/.gitconfig
ln -s ~/.dotfiles/my.cnf ~/.my.cnf

```

Notes:
-----

This repository contains:

* vim config.
* global `gitignore` with ide-generated or persistent files that should be ignored by git, but should not be present in per-project `.gitignore`. They are part of personal development env and not project env.
* global `gitconfig` with couple useful aliases.
* tmux config - with key bindings that are imho very convenient (check them out ;).
* custom mysql/mariadb prompt that shows user, host and database.

