# FitParser-COVIDUS
A .fit file python script for COVIDUS personal health assistant. Garmin fitness equipment export their data to ANT/GARMIN .fit files. These files are binary encoded. This script makes use of python-fitparse Library from  https://github.com/dtcooper/python-fitparse to decode and import GARMIN generated health data to COVIDUS platform.
## Fit Files
* FIT files contain data stored in a binary file format.
* The FIT (Flexible and Interoperable Data Transfer) file protocol is specified by ANT.
* The SDK, code examples, and detailed documentation can be found in the ANT FIT SDK.

## Installation

* Using pip

The easiest way to grab fitparse is using pip,

$ pip install python-fitparse

* From github

Navigate to https://github.com/dtcooper/python-fitparse on github and clone the latest version:

$ git clone git@github.com:dtcooper/python-fitparse.git

$ cd python-fitparse

$ python setup.py install

#work in progress...


## Authors

* **Chris Papathanasiou** <developer@drmac.gr>

* See also the list of  [contributors](https://github.com/crispSV/FitParser-COVIDUS/blob/master/contributors) who participated in this project.


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* This code is initialy written for EUvsVirus Hackathon https://euvsvirus.org/ entry
