# vim configuration

Fairly standard vim configuration to use on remote machines with shortcuts for faster tab/split movement. 

Currently using the Solarized Light colorway and pathogen for package management (crtlp, syntastic, airline, NerdTREE, fugitive).

Also used to interactively work in R via Neovim (https://github.com/jalvesaq/Nvim-R).

Installation:

    git clone git://github.com/nelstrom/dotvim.git ~/.vim

Create symlinks:

    ln -s ~/.vim/vimrc ~/.vimrc
    ln -s ~/.vim/gvimrc ~/.gvimrc

Switch to the `~/.vim` directory, and fetch submodules:

    cd ~/.vim
    git submodule init
    git submodule update
