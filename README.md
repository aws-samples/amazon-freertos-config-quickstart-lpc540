# Amazon FreeRTOS Configuration Quickstart for NXP LPC540 Series Projects

The NXP LPC54018 Iot Module SDKs version 2.5 and 2.6 have slightly divergent and older embedded versions of Amazon FreeRTOS. Missing from this implementation is the aws_config_quick_start tool that automates the creation of Thing Registry entry, policy, certificate, and the installation of the wifi and certificates into the device firmware source.

The tool in the Amazon FreeRTOS 201906.00_Major release is incompatible with the NXP SDK software.

This project holds a modified version of the aws_config_quick_start tool that is compatible with SDK versions 2.5 and 2.6.


After installing the NXP SDK in MCUXpresso and importing an Amazon FreeRTOS based sample, open a terminal window and clone this repo inside the `amazon-freertos` directory with

```
cd </path/to/SDK/sample/root/>amazon-freertos
git clone <this repository url>.git tools
```
*NB-* the above commands put the repo in a tools directory and not a default git repo named directory.

## Usage

Consult the README.md file in the subfolder.

## License
This library is licensed under the Apache 2.0 License. 
