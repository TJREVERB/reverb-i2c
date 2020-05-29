## Project Description
**this package is only meant for use within the TJREVERB pFS codebase**

_use of this package in other projects is not supported and not advised_

reverb-i2c is a custom i2C library meant for use with the Simulator testing suite.
Instead of conducting actual i2C calls to physical hardware, reverb-i2c will save all
data to a local text file which then can be read by the Simulator. More information on 
Simulator [here](https://github.com/TJREVERB/software-in-the-loop.git).

Since this package is meant to override the conventional `smbus2` package, reverb-i2c **MUST**
be installed in a separate virtual environment. 

## Quick Start Testing
To install this package:
```shell script
pip install reverb-i2c
```
* The conventional `smbus2` package, if present will be overridden by installing this package

