Peter's Dotfiles
===============

A home for my dot files. I use thoughtbot's [rcm](https://github.com/thoughtbot/rcm) to install/update the files

Install
-------

Clone down this repo

    git clone git://github.com/peterbsmith2/dotfiles.git ~/.dotfiles

Install [rcm](https://github.com/thoughtbot/rcm):

    brew bundle

Install:

    # install the dotfiles
    rcup -x README.md -x Brewfile
    # setup vim vundle
    git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
    vim +BundleInstall +qall

This creates the symlinks for all files stored in .dotfiles

Additional Software (Install these before dotfiles on a fresh install)
------------------

- [prezto](https://github.com/sorin-ionescu/prezto) as a ZSH framework
- [rbenv](https://github.com/sstephenson/rbenv) for the rubies on mac
- [The Silver Searcher](https://github.com/ggreer/the_silver_searcher) fast file search
