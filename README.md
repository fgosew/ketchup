# ketchup
Ketchup kernel grabber with support for kernel 4.x, fork of debian jessie package version

Attention:
The "ketchup" file in the root folder is for those users who do not use a debian based distribution. It's the patched script version. The one in the debian directory is pre patch and will be patched during package creation according to the debian packaging rules. 


building the debian package:

$ cd ketchup/debian

$ debuild -us -uc
