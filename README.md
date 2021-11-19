About constructor
=================

Home: http://github.com/conda/constructor

Package license: BSD-3-Clause

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/constructor-feedstock/blob/master/LICENSE.txt)

Summary: create installer from conda packages

Development: https://github.com/conda/constructor

Documentation: https://conda.io/projects/conda/en/latest/

Constructor is a tool for constructing an installer for a collection of
conda packages. It creates an Anaconda-like installer consisting of
packages.


Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-constructor-green.svg)](https://anaconda.org/napari/constructor) | [![Conda Downloads](https://img.shields.io/conda/dn/napari/constructor.svg)](https://anaconda.org/napari/constructor) | [![Conda Version](https://img.shields.io/conda/vn/napari/constructor.svg)](https://anaconda.org/napari/constructor) | [![Conda Platforms](https://img.shields.io/conda/pn/napari/constructor.svg)](https://anaconda.org/napari/constructor) |

Installing constructor
======================

Installing `constructor` from the `napari` channel can be achieved by adding `napari` to your channels with:

```
conda config --add channels napari
conda config --set channel_priority strict
```

Once the `napari` channel has been enabled, `constructor` can be installed with:

```
conda install constructor
```

It is possible to list all of the versions of `constructor` available on your platform with:

```
conda search constructor --channel napari
```




Updating constructor-feedstock
==============================

If you would like to improve the constructor recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`napari` channel, whereupon the built conda packages will be available for
everybody to install and use from the `napari` channel.
Note that all branches in the conda-forge/constructor-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@jakirkham](https://github.com/jakirkham/)
* [@jschueller](https://github.com/jschueller/)
* [@mbargull](https://github.com/mbargull/)
* [@msarahan](https://github.com/msarahan/)

