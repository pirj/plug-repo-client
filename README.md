# Plugin repository CLI

This is a command line client for SSH based and command line controlled plugin repository.
Repository's source code is [here](https://github.com/pirj/plug-repo).

As a matter of fact this is a simple wrapper around SSH commands and file based configuration.

## Synopsis

As collaborator:

    $ pr tcsh publish colorize-output https://github.com/pirj/tcsh-colorize-output.git
    $ pr tcsh rm colorize-output

As user:

    $ pr tcsh add tcsh.plug-repo.net
    $ pr tcsh info
    $ pr tcsh ls
    $ pr tcsh fetch colorize-output
    $ pr tcsh register

As owner:

    $ pr tcsh collab john-doe@no-panties.org
    $ pr tcsh uncollab someone-you-thought-you-can-trust@traitor.net

## Author

Philipp Pirozhkov
pirjsuka at gmail com
