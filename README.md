fonts-mlym for Debian
---------------------

This is a dummy package that makes Debian's package management system believe
that equivalents to packages on which other packages do depend on are actually
installed.

The special dependencies used in this package are:

Depends: fonts-lohit-mlym, fonts-smc
Breaks: ttf-malayalam-fonts (<< 2:1.0)
Replaces: ttf-malayalam-fonts

Please note that this is a crude hack and if thoughtlessly used might possibly
do damage to your packaging system. And please note as well that using it is
not the recommended way of dealing with broken dependencies. Better file a bug
report instead.

Deinstallation of this package is only possible when all pending dependency
issues are properly resolved in some other way. A more brutal approach for it's
deinstallation is to create and install the package configured using an empty
control file.
