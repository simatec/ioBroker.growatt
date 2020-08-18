![Logo](admin/glogo.png)
# ioBroker.growatt

[![NPM version](http://img.shields.io/npm/v/iobroker.growatt.svg)](https://www.npmjs.com/package/iobroker.growatt)
[![Downloads](https://img.shields.io/npm/dm/iobroker.growatt.svg)](https://www.npmjs.com/package/iobroker.growatt)
![Number of Installations (latest)](http://iobroker.live/badges/growatt-installed.svg)
![Number of Installations (stable)](http://iobroker.live/badges/growatt-stable.svg)
[![Dependency Status](https://img.shields.io/david/PLCHome/iobroker.growatt.svg)](https://david-dm.org/PLCHome/iobroker.growatt)
[![Known Vulnerabilities](https://snyk.io/test/github/PLCHome/ioBroker.growatt/badge.svg)](https://snyk.io/test/github/PLCHome/ioBroker.growatt)

[![NPM](https://nodei.co/npm/iobroker.growatt.png?downloads=true)](https://nodei.co/npm/iobroker.growatt/)

## growatt adapter for ioBroker

ioBroker Growatt Adapter to communiacte with Growatt Shine Server.
I'm not affiliated.
Usually, the data is sent from the data logger to the cloud every 5 minutes.
The software queries the server every 30 seconds so that the offset is not too great.

Not all plant types are implemented.

Currently only data can be read, writing parameters or changing parameters is not possible.

## Admin Page

### User and Password
Please enter the name and password that you also use in the Shine app or in the web portal.

### Read plant data
This data record contains the stored master data

### Read status data
These data are not available for all plants. This dataset contains live data.

### Read total data
This data record contains aggregation data.

### Read device data
This data record contains some data from the device. Some data are also available in the other categories.

### Read weather
This data set contains the weather forecast




## Changelog

### 0.0.2
* (PLCHome) initial release

### 0.0.1
* (PLCHome) initial release





## License
MIT License

Copyright (c) 2020 PLCHome <https://github.com/PLCHome>

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