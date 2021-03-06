---
title: Linux
---

Linux
=====

Package Manager
---------------

Linux users should be able to use their package manager to install all of this software (if you're
using Linux, we assume you won't have any trouble with these requirements).

However note that if you are running an older Linux distribution you may get older versions with
different look and features.  A recent Linux distribution is recommended.

Python via package manager
--------------------------

Recent versions of Ubuntu pack mostly up to date versions of all needed
packages. The version of IPython might be slightly out of date. Advanced users may wish to upgrade
this using ```pip``` or a manual install. On Ubuntu you should ensure that the following packages
are installed using apt-get.

*  python-numpy
*  python-scipy
*  python-nose
*  python-matplotlib
*  python-pip
*  ipython
*  ipython-notebook

Older distributions may have outdated versions of specific packages.
Other linux distributions most likely also contain the needed python packages but again
they may also be outdated.

Python via Enthought Canopy
---------------------------

Alternatively you may install a complete independent scientific python distribution. One of these is
Enthought Canopy.

The Enthought Canopy python distribution exists in two different versions. A basic free version with
a limited number of packages (Canopy express) and a non free full version. The full version can be
obtained free of charge for academic use. Register with
[Enthought Scientific Computing](https://enthought.com/products/canopy/academic/) using your UCL
e-mail address for an academic licence.

You may then use your Enthought user account to sign into the installed Canopy application and
activate the full academic version. Canopy comes with a package manager from where it is possible to
install and update a large number of python packages. The packages installed by default should cover
our needs.

##Git

If git is not already available on your machine you can try to install it via your distribution
package manager (e.g. `apt-get` or `yum`), for example:

``` bash
sudo apt-get install git
```

Editor
------

Many different text editors suitable for programming are available.  If you don't already have a
favourite, you could look at [Kate](http://kate-editor.org/).

Regardless of which editor you have chosen you should configure git to use it. Executing something
like this in a terminal should work:

``` bash
git config --global core.editor NameofYourEditorHere
```

The default shell is usually bash but if not you can get to bash by opening a terminal and typing
`bash`.

