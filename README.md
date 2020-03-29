About pixman
============

Home: http://www.pixman.org/

Package license: MIT

Feedstock license: BSD 3-Clause

Summary: A low-level software library for pixel manipulation.

Pixman is a low-level software library for pixel manipulation, providing
features such as image compositing and trapezoid rasterization.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/pixman-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_target_platformlinux-64</td>
              <td>
                <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/pixman-feedstock?branchName=master&jobName=linux&configuration=linux_target_platformlinux-64" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_target_platformosx-64</td>
              <td>
                <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/pixman-feedstock?branchName=master&jobName=osx&configuration=osx_target_platformosx-64" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
  <tr>
    <td>Windows</td>
    <td>
      <img src="https://img.shields.io/badge/Windows-disabled-lightgrey.svg" alt="Windows disabled">
    </td>
  </tr>
  <tr>
    <td>Linux_ppc64le</td>
    <td>
      <img src="https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg" alt="ppc64le disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pixman-green.svg)](https://anaconda.org/sdvillal/pixman) | [![Conda Downloads](https://img.shields.io/conda/dn/sdvillal/pixman.svg)](https://anaconda.org/sdvillal/pixman) | [![Conda Version](https://img.shields.io/conda/vn/sdvillal/pixman.svg)](https://anaconda.org/sdvillal/pixman) | [![Conda Platforms](https://img.shields.io/conda/pn/sdvillal/pixman.svg)](https://anaconda.org/sdvillal/pixman) |

Installing pixman
=================

Installing `pixman` from the `sdvillal` channel can be achieved by adding `sdvillal` to your channels with:

```
conda config --add channels sdvillal
```

Once the `sdvillal` channel has been enabled, `pixman` can be installed with:

```
conda install pixman
```

It is possible to list all of the versions of `pixman` available on your platform with:

```
conda search pixman --channel sdvillal
```




Updating pixman-feedstock
=========================

If you would like to improve the pixman recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`sdvillal` channel, whereupon the built conda packages will be available for
everybody to install and use from the `sdvillal` channel.
Note that all branches in the sdvillal/pixman-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@ccordoba12](https://github.com/ccordoba12/)
* [@jakirkham](https://github.com/jakirkham/)
* [@ocefpaf](https://github.com/ocefpaf/)
* [@sdvillal](https://github.com/sdvillal/)

