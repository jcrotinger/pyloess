# pyloess: a numpy wrapper to lowess and stl.

## Build with Conda

* [Install Conda](https://conda.io/docs/install/quick.html "Quick install &mdash; Conda documentation")
* Create conda environment; e.g: `$ conda create -n pyloess python=3.6 gfortran_osx-64 gcc numpy`
* Activate environment: `$ source activate pyloess`
* Clean: `$ rm -rf build/*`
* Install: `$ python setup.py install`

NOTE: On recent version of MacOS you may have to manually install the C include files as some Mojave patches apparently delete them and `xcode-select --install` no longer re-installs them. I found [this](https://stackoverflow.com/a/58000319/2587908) helpful.

* Sanity check:

```
$ python
>>> from pyloess import stl
```


### From original readme:

#### LOWESS

The initial file is available at:
http://netlib.bell-labs.com/netlib/go/lowess.f.gz
Simple to double precision conversion by Pierre GERARD-MARCHANT, 2007/03.


#### STL

The initial file is available at:
http://netlib.bell-labs.com/netlib/a/stl.gz
Simple to double precision conversion by Pierre GERARD-MARCHANT, 2007/03.

