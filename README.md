popel
===

Just a silly [`sopel`](https://sopel.chat) launcher, basically. Inspired by `sl` and `gti`.

Build and Install
-----------------

From source:

    $ make
    $ make install # as root, probably

The default install PREFIX is `/usr/bin`.

You can change the speed of the car at compile time via a cpp-define.
For example:

    $ make CFLAGS=-DGTI_SPEED=100 # default is 50

Usage
-----

Try typing `sopel` really fast, on an unfamiliar keyboard.

Author and License
------------------

    Copyright 2012 by Richard Wossal <richard@r-wos.org>
    Copyright 2017 by Aurel W. and Thomas R. Koll

    Permission to use, copy, modify, distribute, and sell this software
    and its documentation for any purpose is hereby granted without fee,
    provided that the above copyright notice appear in all copies and
    that both that copyright notice and this permission notice appear in
    supporting documentation.  No representations are made about the
    suitability of this software for any purpose.  It is provided "as
    is" without express or implied warranty.

