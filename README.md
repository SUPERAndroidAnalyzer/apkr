# apkr

![alt image](https://github.com/zerjioang/apkr/blob/ui/readme/github-frontal.png)

> **apkr** is the codename for a new malware analysis tool developed by myself for my final degree's project.

## Motivation

<p align="justify">
There is only one reason why someone would spend that kind of money to get malware delivered – because it will pay for itself. The article showed that one specific cybergang’s income from just one flavor of ransomware was almost $400,000 a month.
This shows a very dangerous combination of facts. Getting malware onto a victim’s computer is worth a lot of money, so people will pay handsomely for new exploits to make that happen. This makes exploits worth a lot of money, so people will be motivated to continue creating them.
</p>
> Source: http://lightpointsecurity.com/content/the-motivation-behind-malware

## Brief description

https://github.com/zerjioang/apkr/blob/master/readme/apkr-slides.pdf

## Third party libraries involved

* SSDeep 				based on https://github.com/nunobrito/utils/blob/master/Utils/src/utils/hashing/ssdeep/ssdeep.java
* AXML Parser                           https://code.google.com/archive/p/android4me/downloads
* APKtool 2.1.1                         https://bitbucket.org/iBotPeaches/apktool/downloads
* Gson 2.3.1                            https://github.com/google/gson
* log4j 1.2.17                          https://logging.apache.org/log4j/1.2/download.html
* JADX					https://github.com/skylot/jadx

#Features

* .apk unpacker
* .apk resource decoder
* .apk file enumeration
* .apk file classification and identification
* resource fuzzing and hashing
* native code dump
* certificate analysis
* debug certificate detection
* opcode analysis
* unused opcode detection
* androidManifest.xml analysis
* internal structure analysis
* dalvik bytecode flow analysis
* multipath analysis implementation (not tested)
* CFG generation
* simple reflection resolver
* String classification
* simulated workflow generation
* dynamic rules engine
* ...

## apkr modules

* PSCout data module
* Full Android manifest parser, based on official SDK documentation v23.
* Plugins
* Machine Learning (Weka based) module

## apkr plugins

* Hidden ELF file detector plugin
* Application UID detector plugin
* Privacy plugin
* ...

# Client

* NW.js framework                       http://nwjs.io/
* html5up.net 'ALPHA' template          http://html5up.net/alpha
* AdminLTE Bootstrap 3 Template         https://almsaeedstudio.com/preview
* Bootstrap dialogs 			https://nakupanda.github.io/bootstrap3-dialog/
* Dropzone				http://www.dropzonejs.com/

## Node modules:
```
crypto.js, async.js, base64.js, os, fs
```

# Installation

For installation purposes, it needs
  * Internet Access.
  * Windows, MAC OS or Linux computer.
  * A Brain!

# Contribution

To support this project you can:

  - Post thoughts about new features/optimizations that are important to you
  - Submit bugs using one of following ways:
    * Error stacktrace string and log files.
    * Error log and link to public available apk file.
  
And any other comments will be very appreciate.

#License

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
