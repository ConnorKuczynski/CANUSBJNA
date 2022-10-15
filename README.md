CANUSBJNA
=========

[CANUSB](http://www.canusb.com/) is a dongle that plugs into any PC USB Port and gives an instant CAN connectivity. Drivers for Windows 32 bit and 64 bit are available. It can be treated by software as a standard COM Port. But communicating directly via the driver DLL allows faster communications and higher CAN bus loads. The CANUSBJNA library implements access to the native DLL using [Java Native Access (JNA)](https://github.com/twall/jna).

Features
========

* Implements the complete CANUSB API in plain Java.
* Provides class hierarchy hiding the C-like native interface.

Requirements
============

* Windows XP or above
* CANUSB DLL driver version 2.0.2
* jna.jar and jna-platform.jar from [Java Native Access (JNA)](https://github.com/twall/jna)

Using the Library
=================
* TESTING PUSH CODE TO GITHUB dasasdasdad
* [Getting started](https://github.com/HardwareSpielerei/CANUSBJNA/wiki/Getting-Started)
* [LibraryTest example program](https://github.com/HardwareSpielerei/CANUSBJNA/wiki/LibraryTest-example-program)
* [Logger demo application](https://github.com/HardwareSpielerei/CANUSBJNA/wiki/Logger-demo-application)
* [Version history](https://github.com/HardwareSpielerei/CANUSBJNA/wiki/Version-history)

License
=======

CANUSBJNA is published under [MIT License](http://choosealicense.com/licenses/mit/).

Links
=======

A similar library for the Tiny-CAN dongle is provided by the [TinyCANJNA](http://github.com/HardwareSpielerei/TinyCANJNA) project.
