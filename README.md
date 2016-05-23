Peakcoin integration/staging tree
================================

http://www.peakcoin.org

Copyright (c) 2015 Peakcoin Developers

What is Peakcoin?
----------------

Peakcoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 1 minute block targets
 - ~126 million total coins

The rest is the same as Bitcoin.
 - 12.6 coins per block
 - 5 blocks to retarget difficulty

For more information, as well as an immediately useable, binary version of
the Peakcoin client sofware, see http://www.peakcoin.org.

License
-------

Peakcoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Peakcoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/peakcoin-project/peakcoin/tags) are created
regularly to indicate new official, stable release versions of Peakcoin.