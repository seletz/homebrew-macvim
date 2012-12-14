=============
MacVIM-Seletz
=============

:Author:    Stefan Eletzhofer
:Date:      2012-12-14

Abstract
========

This is a homebrew recipe for my fork of `alloy/macvim` which
installs the latest `split-browser` branch.

Installation
============

To install this, you to remove the regular `macvim` recipe if you
installed it::

        $ brew unlink macvim
        $ brew remove macvim

Then `tap` this recipe::

        $ brew tap seletz/macvim-seletz

Then install it::

        $ brew install --HEAD --override-system-vim macvim-seletz

.. note:: Leave out the `override-system-vim` if you want to keep your
     system `vim` in `/usr/bin/vim`.

.. vim: set ft=rst tw=75 nocin nosi ai sw=4 ts=4 expandtab:
