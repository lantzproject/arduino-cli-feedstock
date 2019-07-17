About arduino-cli
=================

Home: https://github.com/arduino/arduino-cli

Package license: GPLv3

Feedstock license: BSD 3-Clause

Summary: A cli for arduino

arduino-cli is an all-in-one solution that provides builder, boards/library manager,
uploader, discovery and many other tools needed to use any Arduino compatible board and platforms.


Current build status
====================


<table><tr>
    <td>Travis</td>
    <td>
      <a href="https://travis-ci.org/lantzproject/arduino-cli-feedstock">
        <img alt="macOS" src="https://img.shields.io/travis/lantzproject/arduino-cli-feedstock/master.svg?label=macOS">
      </a>
    </td>
  </tr><tr>
    <td>Appveyor</td>
    <td>
      <a href="https://ci.appveyor.com/project/lantzproject/arduino-cli-feedstock/branch/master">
        <img alt="windows" src="https://img.shields.io/appveyor/ci/lantzproject/arduino-cli-feedstock/master.svg?label=Windows">
      </a>
    </td>
  </tr>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/lantzproject/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/lantzproject/feedstock-builds/_apis/build/status/arduino-cli-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux</td>
              <td>
                <a href="https://dev.azure.com/lantzproject/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/lantzproject/feedstock-builds/_apis/build/status/arduino-cli-feedstock?branchName=master&jobName=linux&configuration=linux_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx</td>
              <td>
                <a href="https://dev.azure.com/lantzproject/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/lantzproject/feedstock-builds/_apis/build/status/arduino-cli-feedstock?branchName=master&jobName=osx&configuration=osx_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win</td>
              <td>
                <a href="https://dev.azure.com/lantzproject/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/lantzproject/feedstock-builds/_apis/build/status/arduino-cli-feedstock?branchName=master&jobName=win&configuration=win_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
![ppc64le disabled](https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg)
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-arduino--cli-green.svg)](https://anaconda.org/hgrecco/arduino-cli) | [![Conda Downloads](https://img.shields.io/conda/dn/hgrecco/arduino-cli.svg)](https://anaconda.org/hgrecco/arduino-cli) | [![Conda Version](https://img.shields.io/conda/vn/hgrecco/arduino-cli.svg)](https://anaconda.org/hgrecco/arduino-cli) | [![Conda Platforms](https://img.shields.io/conda/pn/hgrecco/arduino-cli.svg)](https://anaconda.org/hgrecco/arduino-cli) |

Installing arduino-cli
======================

Installing `arduino-cli` from the `hgrecco` channel can be achieved by adding `hgrecco` to your channels with:

```
conda config --add channels hgrecco
```

Once the `hgrecco` channel has been enabled, `arduino-cli` can be installed with:

```
conda install arduino-cli
```

It is possible to list all of the versions of `arduino-cli` available on your platform with:

```
conda search arduino-cli --channel hgrecco
```




Updating arduino-cli-feedstock
==============================

If you would like to improve the arduino-cli recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`hgrecco` channel, whereupon the built conda packages will be available for
everybody to install and use from the `hgrecco` channel.
Note that all branches in the lantzproject/arduino-cli-feedstock are
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


