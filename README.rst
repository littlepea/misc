Misc scripts and tools for development
======================================

Useful commands
---------------

Add commands from `profile_commands`_ into your ~/.profile::

    cat profile_commands >> ~/.profile

You can also add aliases from `profile_aliases`_ into your ~/.profile::

    cat profile_aliases >> ~/.profile

Activate by running::

    source ~/.profile

Git aliases
-----------

Add aliases from `git_aliases`_ into your ~/.gitconfig::

    cat git_aliases >> ~/.gitconfig

Other files
-----------

Copy other useful files to `$HOME` dir::

    cp -R binaries/* ~/bin/

.. _profile_commands: ./profile_commands
.. _profile_aliases: ./profile_aliases
.. _git_aliases: ./git_aliases
