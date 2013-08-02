pkg\_search
===========

A nifty little script for searching for & installing packages in OpenBSD

What does it do?
----------------

pkg\_search searched the users PKG\_PATH for the given string, it then returns a numbered list of package names containing that string and gives the option to install the desired package number using pkg\_add

Caveats
-------

Currently, only those using FTP to install their packages are able to use pkg\_search 
