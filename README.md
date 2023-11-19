About freecad-feedstock
=======================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/freecad-feedstock/blob/main/LICENSE.txt)

Home: https://ondsel.com/

Package license: LGPL-2.1-or-later

Summary: Ondsel is a parametric 3D modeler made primarily to design real-life objects of any size. 

Development: https://github.com/Ondsel-Development/FreeCAD

Documentation: https://wiki.freecad.org/Main_Page

Ondsel is a general purpose feature-based, parametric 3D modeler for
CAD, MCAD, CAx, CAE and PLM, aimed directly at mechanical engineering
and product design but also fits a wider range of uses in engineering,
such as architecture or other engineering specialties. It is 100% Open
Source (LGPL2+ license) and extremely modular, allowing for very
advanced extension and customization.
Ondsel is based on FreeCAD, a free and open source project.


Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-freecad-green.svg)](https://anaconda.org/Ondsel/freecad) | [![Conda Downloads](https://img.shields.io/conda/dn/Ondsel/freecad.svg)](https://anaconda.org/Ondsel/freecad) | [![Conda Version](https://img.shields.io/conda/vn/Ondsel/freecad.svg)](https://anaconda.org/Ondsel/freecad) | [![Conda Platforms](https://img.shields.io/conda/pn/Ondsel/freecad.svg)](https://anaconda.org/Ondsel/freecad) |

Installing freecad
==================

Installing `freecad` from the `Ondsel/label/dev` channel can be achieved by adding `Ondsel/label/dev` to your channels with:

```
conda config --add channels Ondsel/label/dev
conda config --set channel_priority strict
```

Once the `Ondsel/label/dev` channel has been enabled, `freecad` can be installed with `conda`:

```
conda install freecad
```

or with `mamba`:

```
mamba install freecad
```

It is possible to list all of the versions of `freecad` available on your platform with `conda`:

```
conda search freecad --channel Ondsel/label/dev
```

or with `mamba`:

```
mamba search freecad --channel Ondsel/label/dev
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search freecad --channel Ondsel/label/dev

# List packages depending on `freecad`:
mamba repoquery whoneeds freecad --channel Ondsel/label/dev

# List dependencies of `freecad`:
mamba repoquery depends freecad --channel Ondsel/label/dev
```




Updating freecad-feedstock
==========================

If you would like to improve the freecad recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`Ondsel` channel, whereupon the built conda packages will be available for
everybody to install and use from the `Ondsel` channel.
Note that all branches in the conda-forge/freecad-feedstock are
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

* [@adrianinsaval](https://github.com/adrianinsaval/)

