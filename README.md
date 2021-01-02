![Logo](admin/nodedmx.png)
# ioBroker.nodedmx

[![NPM version](http://img.shields.io/npm/v/iobroker.nodedmx.svg)](https://www.npmjs.com/package/iobroker.nodedmx)
[![Downloads](https://img.shields.io/npm/dm/iobroker.nodedmx.svg)](https://www.npmjs.com/package/iobroker.nodedmx)
![Number of Installations (latest)](http://iobroker.live/badges/nodedmx-installed.svg)
![Number of Installations (stable)](http://iobroker.live/badges/nodedmx-stable.svg)
[![Dependency Status](https://img.shields.io/david/Boardman-ger/iobroker.nodedmx.svg)](https://david-dm.org/Boardman-ger/iobroker.nodedmx)
[![Known Vulnerabilities](https://snyk.io/test/github/Boardman-ger/ioBroker.nodedmx/badge.svg)](https://snyk.io/test/github/Boardman-ger/ioBroker.nodedmx)

[![NPM](https://nodei.co/npm/iobroker.nodedmx.png?downloads=true)](https://nodei.co/npm/iobroker.nodedmx/)

**Tests:** ![Test and Release](https://github.com/Boardman-ger/ioBroker.nodedmx/workflows/Test%20and%20Release/badge.svg)

## nodedmx adapter for ioBroker

nodedmx adpter is used to have acces to node-dmx/dmx modules for accessing varios DMX devises as explained here: 

https://github.com/node-dmx/dmx

Actually this devices are supported:

    null: a development driver that prints the universe to stdout
    socketio: a driver which sends out the universe via socket.IO as an array (see demo_socket_client.js as a client example)
    artnet: driver for EnttecODE
    bbdmx: driver for BeagleBone-DMX
    dmx4all: driver for DMX4ALL devices like the "NanoDMX USB Interface"
    enttec-usb-dmx-pro: a driver for devices using a Enttec USB DMX Pro chip like the "DMXKing ultraDMX Micro".
    enttec-open-usb-dmx: driver for "Enttec Open DMX USB". This device is NOT recommended, there are known hardware limitations and this driver is not very stable. (If possible better obtain a device with the "pro" chip)
    dmxking-utra-dmx-pro: driver for the DMXKing Ultra DMX pro interface. This driver support multiple universe specify the options with Port = A or B

I have only tested the dmx4all device together with a nonoDMX Controler.



## Changelog

### 0.1.0
* (Boardman-ger) initial release

## License
MIT License

Copyright (c) 2020 Boardman-ger <Boardman-ger@selzer-schoeneck.de>

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