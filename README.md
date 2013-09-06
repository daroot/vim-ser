vim-ser
=======

Vim syntax for Kamailio files


Overview
--------

Vim scripts to auto-detect SER and Kamailio configuration files and
enable syntax highlighting for them.

Usage
-----

- autodetection is based on .cfg extension and match of #!SER,
#!KAMAILIO (and other variants), modparam or route keywords in
first 400 lines of file. You can enable syntax highlighting for files
not auto-detected with vim command: "setf ser".


Authors:
----------

Copy from kamailio repo, this is only a copy for add with pathogen and git-submodule

Install:
--------
 
 Add this in your vimrc:

  execute pathogen#infect()

Now add this repo in the ~/.vim/bundle directory


