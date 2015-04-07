arch-repo-tox
=============

Tox Arch Linux repository with PKGBUILD scripts for Toxcore, Tox clients, and
other Tox-related projects.

If you encounter an issue, please do not hesitate to file an issue here on
GitHub.

Instructions
------------

    $ git clone https://github.com/Tox/arch-repo-tox
    $ cd arch-repo-tox

    $ cd tox-git
    $ makepkg -si

This will build and install `toxcore` on your system. Repeat the last two steps
for any client or other project you wish to install (many will also require
the `libfilteraudio-git` package).

For more detailed information, please see the [Arch Wiki][1].

[1]: https://wiki.archlinux.org/index.php/Makepkg
