About gorgon-legacy
===================

Home: 

Package license: 

Feedstock license: BSD 3-Clause

Summary: Gorgon, an interactive molecular modeling system



Installing gorgon-legacy
========================

Installing gorgon-legacy from the GorgonCryoEM channel can be achieved by adding GorgonCryoEM to your channels with:

```
conda config --add channels GorgonCryoEM
```

Once the GorgonCryoEM channel has been enabled, gorgon-legacy can be installed with:

```
conda install gorgon-legacy
```

Or gorgon-legacy can be installed with a single command:

```
conda install gorgon-legacy -c GorgonCryoEM
```

It is possible to list all of the versions of gorgon-legacy available on your platform with:

```
conda search gorgon-legacy --channel GorgonCryoEM
```



Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/GorgonCryoEM/gorgon-legacy-feedstock.svg?style=shield)](https://circleci.com/gh/GorgonCryoEM/gorgon-legacy-feedstock)
OSX: [![TravisCI](https://travis-ci.org/GorgonCryoEM/gorgon-legacy-feedstock.svg?branch=master)](https://travis-ci.org/GorgonCryoEM/gorgon-legacy-feedstock)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/GorgonCryoEM/gorgon-legacy-feedstock?svg=True)](https://ci.appveyor.com/project/GorgonCryoEM/gorgon-legacy-feedstock/branch/master)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/gorgoncryoem/gorgon-legacy/badges/version.svg)](https://anaconda.org/gorgoncryoem/gorgon-legacy)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/gorgoncryoem/gorgon-legacy/badges/downloads.svg)](https://anaconda.org/gorgoncryoem/gorgon-legacy)


Updating gorgon-legacy-feedstock
================================

If you would like to improve the gorgon-legacy recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`GorgonCryoEM` channel, whereupon the built conda packages will be available for
everybody to install and use from the `GorgonCryoEM` channel.
Note that all branches in the GorgonCryoEM/gorgon-legacy-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.
