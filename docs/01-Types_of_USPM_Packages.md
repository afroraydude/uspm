# Types of USPM packages

`packagename.uspm` - This is the typical package name. It may be precompiled binaries or it could also be 
sources to be compiled by the `PACKAGECODE` file.

`packagename-src.uspm` - This is a package that is grabbed from source. There are 2 general types accepted:
1. An almost empty structure with a command to pull from a git repo within the `PACKAGECODE` file
or
2. A package with the default `PACKAGECODE` file and just the source files hosted within the package.