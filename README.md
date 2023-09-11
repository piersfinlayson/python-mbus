python-mbus
===========

Python wrapper for [libmbus](http://www.rscada.se/libmbus) ([source](https://github.com/rscada/libmbus))

* installation: 
    * ```sudo apt -y install python3-pip```
    * run ```python setup.py install```
    * install pytest with ```pip install pytest pytest-cov```
    * install libmbus - once done you may also need to ```export LD_LIBRARY_PATH=/usr/local/lib```
* tests: run ```py.test```
    * please adjust the serial device in pytest.ini - on a Pi set this to /dev/ttyAMA0
    * to only run tests involving the serial device, run ```py.test -m serial```

License
=======

This software is licensed under the [BSD license](http://opensource.org/licenses/BSD-3-Clause). 
