#Dotfiles (and general setup options)#
This repo will contain two types of items:

1. Dotfiles which can be symlinked in production
2. Customized configuration files (think nginx config, or pelican config files). Obviously these will need to be:
    - Censored for sensitive informaiton (passwords, etc.)
    - Updateable on new installations (changes to default config should be highlighted/easily-identifable

##Installed Software/Packages##
- [Zsh](https://github.com/McGinn/dotfiles#Zsh)
    - OhMyZsh
- Nginx
- Pelican
    - Elegent theme for Pelican
- Python 3
    - virtualenv (for python 3)
- vim
    - vundle
        - vim-markdown
        - python-mode
- ipython

##<a name="Zsh">Zsh</a>##
- Install ohmyzsh via:
''''
    curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh
''''
- Currently using the default ohmyzsh .vimrc file
- I could probably add a couple of alises and plugins in the future
