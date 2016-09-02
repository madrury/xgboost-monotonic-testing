Demo Of Xgboost Monotonic Functionality
=======================================

This repository contains some initial investigative work into using monotonic constraints in the xgboost library.

Installation
------------

To access the monotonic constraint functionality in xgboost, it is currently necessary to install a development version from source.

First, clone the following repository, using the `recursive` flag to also acquire necessary build tools

```
git clone --recursive https://github.com/tqchen/xgboost.git
```

Then build the xgboost backend

```
cd xgboost
./build.sh
```

Finally, build the python package

```
cd python-package
python setup.py instal
```

Of course, make sure you have the python environment active in which you want to install the development xgboost before running these commands.
