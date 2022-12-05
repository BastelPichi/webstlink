### I tinkered to get the demo directly hosted on github pages, and added support for AT32403RCT6 chip from Artery which is a faster clone of STM32F103RCT6

webstlink
---------
webstlink is a port of [pystlink](https://github.com/pavelrevak/pystlink), using the [WebUSB](https://wicg.github.io/webusb/) API as a backend to control ST-Link/V2 and ST-Link/V2-1 debug probes from the browser.

Check out the live demo [online](https://candas1.github.io/webstlink/) ([video](https://www.youtube.com/watch?v=NmIKtWMw-jw))

Tested features
---------------
* Reading registers
* Reading memory
* Halt/step/run/reset
* Erasing/writing flash (tested on STM32F103 only)

Dependencies
------------
webstlink depends on [WebUSB](https://caniuse.com/#feat=webusb) and many ES6 features.
For best results, test with Chrome 61 or newer.

Local testing
-------------
You can test locally with any webserver. For a one-liner, run:

    python -m SimpleHTTPServer

and navigate to http://localhost:8000/demo/

Licensing
---------
webstlink is available under the terms of the MIT license, the same as the pystlink project.
