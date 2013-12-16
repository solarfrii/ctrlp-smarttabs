CtrlP-SmartTabs
===============

Vim CtrlP plugin to switch between opened tabs.

Synopsis
========
With the vim plugin CtrlP you can easily open a file or a buffer.
This is a ctrlp.vim extension that allow you to switch between different opened tabs.

Prerequisites
=============
In order to use this plugin you need to have [CtrlP](https://github.com/kien/ctrlp.vim) installed.

Installation
============
If you use [Vundle](https://github.com/gmarik/vundle.git) you can install this plugin adding this line:

    Bundle 'DavidEGx/ctrlp-smarttabs'

to your .vimrc file and running the command:

    :BundleInstall

In case you use [pathogen](https://github.com/tpope/vim-pathogen) as a plugin manager you can install it by running:

    $ cd ~/.vim/bundle/
    $ git clone https://github.com/DavidEGx/ctrlp-smarttabs.git


Basic Usage
===========
You can see the list of opened tabs using :CtrlPSmartTabs, there you can select any opened tab and press enter to jump the opened tab.
To use easily just add some mapping to your .vimrc:

    " Just an example from my .vimrc
    nnoremap <F3> :CtrlPSmartTabs<CR>
    nnoremap <F4> :CtrlP<CR>

License
=======
Copyright (C) 2013 David Escribano Garcia. Distributed under GPLv3 license.
