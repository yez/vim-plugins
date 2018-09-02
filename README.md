# Installation


    git clone git@github.com:yez/vim-plugins.git ~/vim-plugins --recursive
    mkdir ~/.vim
    cd ~/.vim
    ln -s ~/vim-plugins/autoload autoload
    ln -s ~/vim-plugins/bundle bundle

## Adding a submodule

    git submodule add $GIT_URL bundle/$PACKAGE_NAME

## Updating submodule

    >= git 1.8.2
    git submodule update --recursive --remote

    git 1.7.3
    git submodule update --recursive

    or:

    git pull --recurse-submodules

    if you want to pull your submodules to latest commits intead of what the repo points to.

    Note: If that's the first time you checkout a repo you need to use --init first:

    git submodule update --init --recursive

    git 1.6.1
    git submodule foreach git pull origin master

## Command-T installation

    (optional) rvm use sytem
    cd ~/vim-plugins/bundle/command-t/ruby/command-t/ext/command-t
    ruby extconf.rb
    make
