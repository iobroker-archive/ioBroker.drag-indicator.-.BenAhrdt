![Logo](admin/drag-indicator.png)
# ioBroker.drag-indicator

[![NPM version](https://img.shields.io/npm/v/iobroker.janitza-gridvis.svg)](https://www.npmjs.com/package/iobroker.drag-indicator)
[![Downloads](https://img.shields.io/npm/dm/iobroker.janitza-gridvis.svg)](https://www.npmjs.com/package/iobroker.drag-indicator)
![Number of Installations](https://iobroker.live/badges/drag-indicator-installed.svg)
![Current version in stable repository](https://iobroker.live/badges/drag-indicator-stable.svg)
[![Dependency Status](https://img.shields.io/david/BenAhrdt/iobroker.janitza-gridvis.svg)](https://david-dm.org/BenAhrdt/iobroker.drag-indicator)

[![NPM](https://nodei.co/npm/iobroker.janitza-gridvis.png?downloads=true)](https://nodei.co/npm/iobroker.drag-indicator/)

**Tests:** ![Test and Release](https://github.com/BenAhrdt/ioBroker.drag-indicator/workflows/Test%20and%20Release/badge.svg)

## drag-indicator adapter for ioBroker

Shows the min and max of a selected value (of type number)
So you can catch the extreme values of an state in a desired timerange.
e.g. you can use it for power or temperature values.

## Changelog
<!--
	Placeholder for the next version (at the beginning of the line):
	### **WORK IN PROGRESS**
-->

### 2.0.1 (2022-06-08) - Bugfix unsubscribe additional value
* (BenAhrdt) Do not unsubscribe additional values with deactivate object

### 2.0.0 (2022-06-04)
* (BenAhrdt) deploy implemented

### 1.14.9
* (BenAhrdt) fixed some changes in readme

### 1.14.8
* (BenAhrdt) change setForeignState to setState to write internal States

### 1.14.7
* (BenAhrdt) first official version

## License
MIT License

Copyright (c) 2022 BenAhrdt <bsahrdt@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.