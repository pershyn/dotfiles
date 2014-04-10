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
* global git ignore with ide stuff that should not be ignored per project (part of personal env and not project env).
* global git config with couple handy alliases.
* tmux config - with key bindings that are imho very convenient (check them out ;)


