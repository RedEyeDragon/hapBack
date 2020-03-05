# hapBack

## Description
The hapBack is a wearable technology designed to communicate distance through haptics.

## Installation
curl -L http://coreelec.io/33 | bash

To compile and install the library, follow the steps below.

First, install the dependencies required to download and install the library:

sudo apt-get update
sudo apt-get install build-essential python-dev git scons swig
Next, download the files and build the library:
$ git clone https://github.com/jgarff/rpi_ws281x.git
$ cd rpi_ws281x
$ scons

Finally, install the Python wrapper:
$ cd python
$ sudo python setup.py install
