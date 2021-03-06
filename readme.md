My "dotfiles"
-------------

This repository contains my system and development configuration files, often referred to as "dot files" since they are often prefixed with a dot character. The dot has been removed for easy viewing (otherwise it would look like this repository contained no files).

To use the files, you either symlink to them or copy them into place. For instance, here's how you setup the bash configuration:

    ln -s `pwd`/bashrc $HOME/.bashrc
    ln -s `pwd`/bash_profile $HOME/.bash_profile
    ln -s `pwd`/bash $HOME/.bash
    
There is also a script to configure the Gnome desktop and other applications that use dconf/gconf. You may want to inspect the configuration options first, tweaking or removing those you don't want. Then, run the script:

    ./gnome-desktop-settings.sh

The launchers directory contains various launcher files that you link into $HOME/.local/share/applications/

See also: https://github.com/matthewmccullough/dotfiles
