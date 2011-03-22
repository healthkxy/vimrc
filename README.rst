My Vim Stuff
============

I. Organization
---------------

* autoload/ [pathogen.vim lives here]
* bundle/ [all other plugins, managed by pathogen]
* colors/ [color schemes]
* vimrc [the .vimrc file]

II. Vim Version
---------------

I use gVim 7.3 compiled by myself on Ubuntu 10.10. Here's the configure options:::

    ./configure --prefix=/usr --disable-nls --disable-netbeans --disable-darwin --enable-pythoninterp=yes --enable-rubyinterp --enable-gnome-check=yes --enable-fontset --enable-cscope --with-features=huge --enable-multibyte

III. Installation
-----------------

1. Clone this repo:::

    git clone git://github.com/iwinux/vimrc.git

2. In your ~/.vimrc, add the following line:::

    source ~/path/to/vimrc/vimrc

3. Fetch submodules:::

    git submodule init
    git submodule update

That's it, enjoy!
