About ondsel-es-feedstock
=========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/ondsel-es-feedstock/blob/main/LICENSE.txt)

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
| [![Conda Recipe](https://img.shields.io/badge/recipe-ondsel--es-green.svg)](https://anaconda.org/Ondsel/ondsel-es) | [![Conda Downloads](https://img.shields.io/conda/dn/Ondsel/ondsel-es.svg)](https://anaconda.org/Ondsel/ondsel-es) | [![Conda Version](https://img.shields.io/conda/vn/Ondsel/ondsel-es.svg)](https://anaconda.org/Ondsel/ondsel-es) | [![Conda Platforms](https://img.shields.io/conda/pn/Ondsel/ondsel-es.svg)](https://anaconda.org/Ondsel/ondsel-es) |

Installing ondsel-es
====================

Installing `ondsel-es` from the `Ondsel` channel can be achieved by adding `Ondsel` to your channels with:

```
conda config --add channels Ondsel
conda config --set channel_priority strict
```

Once the `Ondsel` channel has been enabled, `ondsel-es` can be installed with `conda`:

```
conda install ondsel-es
```

or with `mamba`:

```
mamba install ondsel-es
```

It is possible to list all of the versions of `ondsel-es` available on your platform with `conda`:

```
conda search ondsel-es --channel Ondsel
```

or with `mamba`:

```
mamba search ondsel-es --channel Ondsel
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search ondsel-es --channel Ondsel

# List packages depending on `ondsel-es`:
mamba repoquery whoneeds ondsel-es --channel Ondsel

# List dependencies of `ondsel-es`:
mamba repoquery depends ondsel-es --channel Ondsel
```




Updating ondsel-es-feedstock
============================

If you would like to improve the ondsel-es recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`Ondsel` channel, whereupon the built conda packages will be available for
everybody to install and use from the `Ondsel` channel.
Note that all branches in the conda-forge/ondsel-es-feedstock are
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

