# Installation


    git clone git@github.com:yez/vim-plugins.git ~/vim-plugins --recursive
    mkdir ~/.vim
    cd ~/.vim
    ln -s ~/vim-plugins/autoload autoload
    ln -s ~/vim-plugins/bundle bundle

## Adding a submodule

    git submodule add $GIT_URL bundle/$PACKAGE_NAME

## Command-T installation

    (optional) rvm use sytem
    cd ~/vim-plugins/bundle/command-t/ruby/command-t/ext/command-t
    ruby extconf.rb
    make
