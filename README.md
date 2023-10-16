# XCP-ng 9

This repository is devoted to the development of the upcoming XCP-ng 9 platform.

![](https://xcp-ng.org/assets/img/mainlogo.png)

## Objectives

Our aim is to test and evaluate various platforms to ascertain the most suitable one for the upcoming major release of XCP-ng (version 9.0). The major focus is on implementing a modern userspace with an updated kernel, OVS, and other features.

Furthermore, we strive to rapidly establish a test platform to solicit early community feedback during the development cycle.

## Prerequisites 

* Complete Python 3 integration (Includes SMAPI and others).
* Either removal or porting of the current Linux kernel blk-tap patch in XAPI/SMAPI to support a recent kernel (6.0 +).
* Execution of XAPI in a brand new "context" (involving the replacement of older components and carrying out specific tests).
* Use of an existing, reliable platform that offers long-term support (LTS), preferably compatible with "Enterprise Linux" (kernel excluded).

## Progress and Feedback

Work is currently underway.