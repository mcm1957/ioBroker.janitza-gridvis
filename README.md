![Logo](admin/janitza-gridvis.png)
# ioBroker.janitza-gridvis

[![NPM version](https://img.shields.io/npm/v/iobroker.janitza-gridvis.svg)](https://www.npmjs.com/package/iobroker.janitza-gridvis)
[![Downloads](https://img.shields.io/npm/dm/iobroker.janitza-gridvis.svg)](https://www.npmjs.com/package/iobroker.janitza-gridvis)
![Number of Installations](https://iobroker.live/badges/janitza-gridvis-installed.svg)
![Current version in stable repository](https://iobroker.live/badges/janitza-gridvis-stable.svg)
[![Dependency Status](https://img.shields.io/david/BenAhrdt/iobroker.janitza-gridvis.svg)](https://david-dm.org/BenAhrdt/iobroker.janitza-gridvis)

[![NPM](https://nodei.co/npm/iobroker.janitza-gridvis.png?downloads=true)](https://nodei.co/npm/iobroker.janitza-gridvis/)

**Tests:** ![Test and Release](https://github.com/BenAhrdt/ioBroker.janitza-gridvis/workflows/Test%20and%20Release/badge.svg)

## janitza-gridvis adapter for ioBroker

Read out data from Energymanagementsystem Janitza® GridVis®.
Your are able to read out all online values of the present devices.
Additional you are able to read out the historical energy values
of the present devices.
Implemented are the following times:
	Today
	Yesterday
	ThisWeek
	LastWeek
	ThisMonth
	LastMonth
	ThisQuarter
	LastQuarter
	ThisYear
	LastYear

## Changelog
<!--
	Placeholder for the next version (at the beginning of the line):
	### **WORK IN PROGRESS**
-->

### 2.0.10 (2022-06-15) - config improoved
* (BenAhrdt) sort values keys before writing into json config

### 2.0.9 (2022-06-14) - implement icson and water consumption
* (BenAhrdt) implements icons for device channel
* (BenAhrdt) implements water consumption for historic values

### 2.0.8 (2022-06-13) - logging language changed
* (BenAhrdt) logging changed into english

### 2.0.7 (2022-06-12) - bugfix translation
* (BenAhrdt) german translation was lost => re-implemented

### 2.0.6 (2022-06-12) - set devices to type channel
* (BenAhrdt) deviceschanged to type channel
* (BenAhrdt) onlineValues & historicValues "folder" changed to "channel"

### 2.0.5 (2022-06-12) - reconnect count in info states
* (BenAhrdt) reconnect count was implemeted into the info states
* (BenAhrdt) set the default value of reconnection before warning to 4 (4 x timeout + 3 x 10s)

### 2.0.4 (2022-06-12) - nuber of reconnection before warning in config
* (BenAhrdt) count the reconnection and warn after configed count is reached 

### 2.0.3 (2022-06-09) - sequential historical read out
* (BenAhrdt) sequential readout of historical data 

### 2.0.2 (2022-06-06) - translation without debug logging
* (BenAhrdt) debug logging for translation removed

### 2.0.1 (2022-06-06) - message translating
* (BenAhrdt) message translating in i18n

### 2.0.0 (2022-06-05)
* (BenAhrdt) bugfixes for first release

### 1.5.5
* (BenAhrdt) readme fixed

### 1.5.4
* (BenAhrdt) upgrading readme

### 1.5.3
* (BenAhrdt) Comment some functions (dev internal)


### 1.5.2
* (BenAhrdt) setting toppics and update readme

### 1.5.1
* (BenAhrdt) reconnection implemented

### 1.5.0
* (BenAhrdt) first version of the adapter

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