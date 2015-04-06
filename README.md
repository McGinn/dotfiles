Dotfiles (and general setup options)
====================================
This repo will contain two types of items:

1. Dotfiles which can be symlinked in production
2. Customized configuration files (think nginx config, or pelican config files). Obviously these will need to be:
    - Censored for sensitive informaiton (passwords, etc.)
    - Updateable on new installations (changes to default config should be highlighted/easily-identifable

I've attempted to order these logically by order of installation. Maybe someday I'll figure out how to write a script to symlink all of these on whatever OS I'm using.

Installed Software/Packages
---------------------------
- [Vim](#vim)
    - vundle
        - vim-markdown
        - python-mode
- [Zsh](#zsh)
    - OhMyZsh
- [Python 3](#python)
    - virtualenv (for python 3)
- [iPython](#ipython)
- [Pelican](#pelican)
    - Elegent theme for Pelican
- [Nginx](#nginx)

##Vim##

##Zsh##
- Install ohmyzsh via:
```zsh
curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh
```
- Currently using the default ohmyzsh .vimrc file
- I could probably add a couple of alises and plugins in the future

##Python##

##iPython##

##Pelican##

##Nginx##
Currently I run three distinct nginx config files:

1. iPython
2. Pelican blog
3. Shellinabox
 
