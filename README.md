# Installation


    git clone git@github.com:yez/vim-plugins.git ~/vim-plugins --recursive
    mkdir ~/.vim
    cd ~/.vim
    ln -s ~/vim-plugins/autoload autoload
    ln -s ~/vim-plugins/bundle bundle


## Command-T installation

    (optional) rvm use sytem
    cd ~/vim-plugins/bundle/command-t/ruby/command-t/ext/command-t
    ruby extconf.rb
    make
