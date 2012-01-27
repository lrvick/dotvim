# lrvick's .vim setup #

<http://github.com/lrvick/dotvim>

## About ##

So let's face it. Stock vim on most machines is pretty painful for a seasoned
programmer. Thing like managing history, proper language indention, syntax
checking auto complete etc, are just not there. To that end, here is my setup
that I have lovingly refined though many years of vimming. Vim, with this
setup, is the only IDE I use. (Yes, I just called vim an IDE. Deal.)

## Current Features ##

  * NerdTree - nice tree-view file browsing [F2]
  * Command-T - fuzzy searching to quickly switch files [Meta-T]
  * Conque-Shell - built in terminals [F3] & [F4]
  * Gundo - undo history managment [F5]
  * Tagbar - easily browse through a programs structure [F9]
  * Supertab - tab-complete anything you have used in the curent buffer
  * Fugitive - built in Git management
  * Syntastic - syntax checking and correction helpers for most major languages
  * Vim-Indent-Guides - easily see indentions. customized to match Solarized
  * Pathogen - for easily managing plugins as git submodules
  * Other various helper plugins to aid programming as I find them useful

## Usage / Installation ##

1. Clone .vim directory

    ```bash
    git clone https://github.com/lrvick/dotvim.git ~/.vim
    ```
2. Install submodules

    ```bash
    cd ~/.vim
    git submodule init
    git submodule update
    ```

3. Install dummy vimrc file

    ```bash
    echo "runtime vimrc" > ~/.vimrc
    ```
## Notes ##

    Questions/Comments? You can find me on IRC: lrvick @ irc://irc.freenode.net
