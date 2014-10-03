python_sample_project
=====================

This Python package...

Authors:

    Peter Polidoro <polidorop@janelia.hhmi.org>

License:

    BSD

##Example Usage


```python
from arduino_device import ArduinoDevice
dev = ArduinoDevice()
dev.get_arduino_device_info()
dev.get_arduino_commands()
```

##Installation

###Linux and Mac OS X

```shell
mkdir -p ~/virtualenvs/arduino_device
virtualenv ~/virtualenvs/arduino_device
source ~/virtualenvs/arduino_device/bin/activate
pip install https://github.com/JaneliaSciComp/python_arduino_device/tarball/master
```

###Windows

Download Python 2.7.X Windows Installer from:

[https://www.python.org/download](https://www.python.org/download)

Add to path:

    C:\Python27\

Download get-pip.py from:

[https://bootstrap.pypa.io/get-pip.py](https://bootstrap.pypa.io/get-pip.py)

Run:

```shell
python get-pip.py
```

Add to path:

    C:\Python27\Scripts\

Run:

```shell
pip install virtualenv
mkdir C:\virtualenvs
virtualenv C:\virtualenvs\arduino_device
C:\virtualenvs\arduino_device\Scripts\activate
pip install https://github.com/JaneliaSciComp/python_arduino_device/zipball/master
```
