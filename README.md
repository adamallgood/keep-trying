keep-trying
===========

The `keep-trying` command executes a given command every X minutes, and stops after Y minutes, or when the command succeeds. It's useful for trying to run a command that, for example, uses input data that may or may not be available yet.

Installing
----------

Clone the repo:

    $ git clone https://github.com/mikecharles/keep-trying.git

Install:

    $ make install

This will install the `keep-trying` script in `~/bin` (it will create the `~/bin` directory if it doesn't already exist).