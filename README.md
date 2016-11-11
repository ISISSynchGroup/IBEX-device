# IBEX-device
A class defining the parent object for all device classes.

## Installation
Releases can be installed manually or with [Bower](https://bower.io/)

### Manual Installation
Download the source [manually](../../releases/latest) from the release page.

Unzip the files into a directory called *dependencies* in the parent directory that contains your project's *.lvproj* file; this is to enable LabVIEW to resolve any file location changes more easily.

```bash
bower install https://github.com/ISISSynchGroup/IBEX-device.git#<release>
```

### Installation with Bower

Bower users should add the following to their project's .bowerrc file:
```javascript
  "directory":"dependencies"
```
Then install with

```bash
bower install https://github.com/ISISSynchGroup/IBEX-device.git#<release>
```
``<release>`` should be chosen from the [release](../../releases) page and will something like *v0.0.1*

## Requirements
* LabVIEW 2015 (SP1)

### Development Requirents
* JKI VIPM (Free Edition)
* JKI [Caraya](https://github.com/JKISoftware/Caraya)
