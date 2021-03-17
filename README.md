About phonopy
=============

Home: https://atztogo.github.io/phonopy/

Package license: BSD-3-Clause

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/phonopy-feedstock/blob/master/LICENSE.txt)

Summary: Phonopy is an open source package for phonon calculations at harmonic and quasi-harmonic levels.

Development: https://github.com/atztogo/phonopy/

Documentation: https://atztogo.github.io/phonopy/

Phonopy is an open source package for phonon calculations at harmonic and quasi-harmonic levels.
It works with multiple DFT programs (VASP, VASP DFPT, Abinit, Pwscf, Siesta, Elk, FHI-aims, Wien2k)
as sources of inter-atomic forces and uses finite displacement method and symmetry relations
for calculating elements of dynamical matrix. It works for all crystal symmetries and provides
(among others)  phonon band structure, phonon DOS and partial-DOS, phonon thermal properties
(free energy, heat capacity, and entropy), phonon group velocity, mean square displacements,
irreducible representations of normal modes, quasi-harmonic approximation (thermal expansion,
heat capacity at constant pressure), mode Grüneisen parameters, non-analytical-term correction
(LO-TO splitting). It also provides Python API for use as a library.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=775&branchName=master">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/phonopy-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_numpy1.16python3.6.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=775&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/phonopy-feedstock?branchName=master&jobName=linux&configuration=linux_64_numpy1.16python3.6.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_numpy1.16python3.7.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=775&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/phonopy-feedstock?branchName=master&jobName=linux&configuration=linux_64_numpy1.16python3.7.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_numpy1.16python3.8.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=775&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/phonopy-feedstock?branchName=master&jobName=linux&configuration=linux_64_numpy1.16python3.8.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_numpy1.19python3.9.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=775&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/phonopy-feedstock?branchName=master&jobName=linux&configuration=linux_64_numpy1.19python3.9.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_numpy1.16python3.6.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=775&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/phonopy-feedstock?branchName=master&jobName=osx&configuration=osx_64_numpy1.16python3.6.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_numpy1.16python3.7.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=775&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/phonopy-feedstock?branchName=master&jobName=osx&configuration=osx_64_numpy1.16python3.7.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_numpy1.16python3.8.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=775&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/phonopy-feedstock?branchName=master&jobName=osx&configuration=osx_64_numpy1.16python3.8.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_numpy1.19python3.9.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=775&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/phonopy-feedstock?branchName=master&jobName=osx&configuration=osx_64_numpy1.19python3.9.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_numpy1.16python3.6.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=775&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/phonopy-feedstock?branchName=master&jobName=win&configuration=win_64_numpy1.16python3.6.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_numpy1.16python3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=775&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/phonopy-feedstock?branchName=master&jobName=win&configuration=win_64_numpy1.16python3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_numpy1.16python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=775&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/phonopy-feedstock?branchName=master&jobName=win&configuration=win_64_numpy1.16python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_numpy1.19python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=775&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/phonopy-feedstock?branchName=master&jobName=win&configuration=win_64_numpy1.19python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-phonopy-green.svg)](https://anaconda.org/conda-forge/phonopy) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/phonopy.svg)](https://anaconda.org/conda-forge/phonopy) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/phonopy.svg)](https://anaconda.org/conda-forge/phonopy) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/phonopy.svg)](https://anaconda.org/conda-forge/phonopy) |

Installing phonopy
==================

Installing `phonopy` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `phonopy` can be installed with:

```
conda install phonopy
```

It is possible to list all of the versions of `phonopy` available on your platform with:

```
conda search phonopy --channel conda-forge
```


About conda-forge
=================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating phonopy-feedstock
==========================

If you would like to improve the phonopy recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/phonopy-feedstock are
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

* [@atztogo](https://github.com/atztogo/)
* [@bocklund](https://github.com/bocklund/)
* [@jochym](https://github.com/jochym/)

