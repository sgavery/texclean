texclean
========

Yet another script for cleaning up after LaTeX

LaTeX compilation generates a lot of files aside from the final document; this script removes them. 
This is useful for maintaining a clean file system and for resolving certain classes of LaTeX bugs.

Key features
------------
* moves files to system trash instead of deletes them.
* verbose and interactive modes.
* a fairly comprehensive table of generated file extensions with descriptions.
* optional flags to only remove certain classes of generated files (logs, auxillary, or include).
* can choose to delete all LaTeX generated files in a directory or only those associated with a latex source file.

Requirements
------------
* python 3
* requires `send2trash` package

Usage
-----

Use `texclean -h` for usage details.
