About sqlite
============

Home: http://www.sqlite.org/

Package license: Public-Domain (http://www.sqlite.org/copyright.html)

Feedstock license: BSD-3-Clause

Summary: Implements a self-contained, zero-configuration, SQL database engine

SQLite is a self-contained, high-reliability, embedded, full-featured,
public-domain, SQL database engine.It is the most used database engine
in the world.


Current build status
====================


<table><tr>
    <td>Travis</td>
    <td>
      <a href="https://travis-ci.com/ramonaoptics/sqlite-feedstock">
        <img alt="macOS" src="https://img.shields.io/travis/com/ramonaoptics/sqlite-feedstock/master.svg?label=macOS">
      </a>
    </td>
  </tr><tr>
    <td>Drone</td>
    <td>
      <a href="https://cloud.drone.io/ramonaoptics/sqlite-feedstock">
        <img alt="linux" src="https://img.shields.io/drone/build/ramonaoptics/sqlite-feedstock/master.svg?label=Linux">
      </a>
    </td>
  </tr>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/sqlite-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/sqlite-feedstock?branchName=master&jobName=linux&configuration=linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/sqlite-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/sqlite-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/sqlite-feedstock?branchName=master&jobName=osx&configuration=osx_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/sqlite-feedstock?branchName=master&jobName=osx&configuration=osx_arm64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/sqlite-feedstock?branchName=master&jobName=win&configuration=win_64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-sqlite-green.svg)](https://anaconda.org/ramonaoptics/sqlite) | [![Conda Downloads](https://img.shields.io/conda/dn/ramonaoptics/sqlite.svg)](https://anaconda.org/ramonaoptics/sqlite) | [![Conda Version](https://img.shields.io/conda/vn/ramonaoptics/sqlite.svg)](https://anaconda.org/ramonaoptics/sqlite) | [![Conda Platforms](https://img.shields.io/conda/pn/ramonaoptics/sqlite.svg)](https://anaconda.org/ramonaoptics/sqlite) |

Installing sqlite
=================

Installing `sqlite` from the `ramonaoptics` channel can be achieved by adding `ramonaoptics` to your channels with:

```
conda config --add channels ramonaoptics
```

Once the `ramonaoptics` channel has been enabled, `sqlite` can be installed with:

```
conda install sqlite
```

It is possible to list all of the versions of `sqlite` available on your platform with:

```
conda search sqlite --channel ramonaoptics
```




Updating sqlite-feedstock
=========================

If you would like to improve the sqlite recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`ramonaoptics` channel, whereupon the built conda packages will be available for
everybody to install and use from the `ramonaoptics` channel.
Note that all branches in the ramonaoptics/sqlite-feedstock are
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

* [@jakirkham](https://github.com/jakirkham/)
* [@jjhelmus](https://github.com/jjhelmus/)
* [@mingwandroid](https://github.com/mingwandroid/)
* [@msarahan](https://github.com/msarahan/)
* [@ocefpaf](https://github.com/ocefpaf/)
* [@snorfalorpagus](https://github.com/snorfalorpagus/)

