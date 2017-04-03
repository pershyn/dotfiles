My .dotfiles repository:
=======================

Vim setup is using [neobundle](https://github.com/Shougo/neobundle.vim).

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

# clone neobunde (before running vim)
git clone https://github.com/Shougo/neobundle.vim ~/.vim/bundle/neobundle.vim
```
On the first start vim will ask to install bundles, example below. Agree :-)

```
Not installed bundles:  ['vimproc', 'vim-instant-markdown', 'VimClojure', 'plantuml-syntax']
Install bundles now?
(y)es, [N]o: y
```

Notes:
-----

This repository contains:

* vim config (with neobundle).
* global `gitignore` with ide-generated or persistent files that should be ignored by git, but should not be present in per-project `.gitignore`. They are part of personal development env and not project env.
* global `gitconfig` with couple useful alliases.
* tmux config - with key bindings that are imho very convenient (check them out ;).
* custom mysql/mariadb prompt that shows user, host and database.

