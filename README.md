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

[Setup Python for Linux](./PYTHON_SETUP_LINUX.md)

[Setup Python for Mac OS X](./PYTHON_SETUP_MAC_OS_X.md)

```shell
mkdir -p ~/virtualenvs/arduino_device
virtualenv ~/virtualenvs/arduino_device
source ~/virtualenvs/arduino_device/bin/activate
pip install https://github.com/JaneliaSciComp/python_arduino_device/tarball/master
```

###Windows

[Setup Python for Windows](./PYTHON_SETUP_WINDOWS.md)

```shell
virtualenv C:\virtualenvs\arduino_device
C:\virtualenvs\arduino_device\Scripts\activate
pip install https://github.com/JaneliaSciComp/python_arduino_device/zipball/master
```
