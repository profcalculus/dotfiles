profcalculus dotfiles for linux home folder.

dependencies
------------
* ctags
* python
    * pep8
    * pyflakes
    * rope

install
-------
Get the dotfiles with:
```
    git clone https://github.com/profcalculus/dotfiles ~/dotfiles
```

To install:
```
    cd ~/dotfiles
    ./install.sh
```

Note: dotfiles and folders start with _ and are appropriately
      linked by the install script.

vim
----
Mostly stolen from https://github.com/theunsa/dotfiles 
Followed the instructions at http://sontek.net/blog/detail/turning-vim-into-a-modern-python-ide with a few customisations and changes of my own including:
* Using Vundle instead of pathogen
* Used CtrlP instead of command-t (no Rake dependency needed)

  (See README in _vim folder for more info)
