
SPF13-VIMEDA
============

## spf12-vimeda: Robert Ekendahl's EDA fork of the excellent spf13-vim distro

VIMEDA is a distribution of vim plugins and resources aimed at EDA developers.
It works with Vim, Gvim, and [MacVim] on Linux, Windows and Mac. It's easy to
install (see below) yet VERY configurable. You can be up and running within a
couple of minutes running the automatic installer. It supports all common
Design and Verification languages including Verilog, SystemVerilog, VHDL,
SystemC, C++ etc. 

I take little credit for this work! VIMEDA is a fork of the excellent
[spf13-vim] distrobution with added packages for Electronic Design and
Verification languages.
 
# Installation

## Linux, \*nix, Mac OSX Installation

The easiest way to install spf13-vim is to use our [automatic installer](http://bit.ly/vimeda) by simply
copying and pasting the following line into a terminal. This will install
spf13-vim and backup your existing vim configuration. If you are upgrading from
a prior version (before 3.0) this is also the recommended installation.

*Requires Git 1.7+ and Vim 7.3+*

```bash
    curl http://bit.ly/vimeda -L > vimeda.sh && sh vimeda.sh
```

If you have a bash-compatible shell you can run the script directly:
```bash

    sh <(curl http://bit.ly/vimeda -L)
```

## Installing on Windows

I have not updated the Windows install scripts so for now this will not work. Hope to update these scripts and add instructions in the future.
Below is more information from the base [spf13-vim] distribution.

Enjoy!

[spf13-vim]:https://github.com/spf13/spf13-vim

