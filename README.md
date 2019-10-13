# General installer for GridLAB-D

To run the build/installer, type the following at the command prompt (or copy and paste):
~~~
curl https://raw.githubusercontent.com/dchassin/gridlabd-install/master/install | bash
~~~

## Changing the repository

To change the repository use the `GRIDLABD_REPO` environment variable:
~~~
export GRIDLABD_REPO=https://github.com/user/repo
curl https://raw.githubusercontent.com/dchassin/gridlabd-install/master/install | bash
~~~
The default repository is currently `https://github.com/dchassin/gridlabd`.

## Changing the branch

To change the repository use the `GRIDLABD_REPO` environment variable:
~~~
export GRIDLABD_BRANCH=branch
curl https://raw.githubusercontent.com/dchassin/gridlabd-install/master/install | bash
~~~
The default branch is currently `master`

## Changing the install options

To change the installation options use the `GRIDLABD_INSTALL_OPTIONS` environment variable
~~~
export GRIDLABD_INSTALL_OPTIONS=--verbose
curl https://raw.githubusercontent.com/dchassin/gridlabd-install/master/install | bash
~~~
The default installation options is currently an empty string.
