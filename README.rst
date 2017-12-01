ESP-IDF template app forked for including VSCode setup into project and configuring for my personal setup.  Contains setup information to integrate in VSCode as well as OpenOCD and GDB debugging setup.

If you found this repo and would like to use it, feel free.  It is provided AS-IS.

Assumes the use of the ESP-WROVER-KIT (mine is V2) and Windows.

Tasks Added:
build-app - builds the app
clean - clean the app
menuconfig - runs 'make menuconfig' - if run from VSCode, will start a interactive terminal verison
flash - build and flash the app
monitor - runs 'make monitor', starting the ESP-IDF python monitor tool
openocd - starts the OpenOCD server (required to be running before debugging)

Other changes from ESP-IDF default template:
- changed component 'main' LOCAL_LOG_LEVEL to ESP_LOG_DEBUG (via component.mk)

ESP-IDF template app
====================

This is a template application to be used with `Espressif IoT Development Framework`_ (ESP-IDF).

Please check ESP-IDF docs for getting started instructions.

Code in this repository is Copyright (C) 2016 Espressif Systems, licensed under the Apache License 2.0 as described in the file LICENSE.

.. _Espressif IoT Development Framework: https://github.com/espressif/esp-idf


