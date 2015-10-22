arch-repo-tox
=============

The Tox Arch Linux repository with PKGBUILD scripts for Toxcore, Tox clients,
and other Tox-related projects.

Instructions
------------

    $ git clone https://github.com/Tox/arch-repo-tox
    $ cd arch-repo-tox

    $ cd toxcore-git
    $ makepkg -si

This will build and install `toxcore` on your system. Repeat the last two steps
for any client or other project you wish to install (many will also require the
`libfilteraudio-git` package).

For more information on building packages, please see the Arch Wiki:
https://wiki.archlinux.org/index.php/Makepkg

Unverified packages
-------------------
Packages that are untested or works in progress are contained in the
`unverified` directory. These might work but they haven't vetted by anyone yet,
use them at your own peril!

Contact
-------
If you need help or you would like to submit patches, please seek the
appropriate channel below.

* IRC Channel:          #tox-dev @ chat.freenode.net
* Mailing list:         dev@lists.tox.chat
* Github Issue tracker: https://github.com/Tox/arch-repo-tox/issues

