# 🤖 OctoPiRestreamer

*The latest OctoPi release with the latest OctoPrint already included and [restreamer](https://datarhei.github.io/restreamer/) pre-installed as a replacement for mjpgstreamer.*

This repository automatically updates the OctoPrint installation on the latest OctoPi image
and provides the resulting image ready to flash. Checkout the [releases](https://github.com/jneilliii/OctoPiWiFi/releases).

## How does this work?

A simple update script is run via [CustoPiZer](https://github.com/OctoPrint/CustoPiZer).
All that is done is running the equivalent of `pip install -U OctoPrint==<latest version>`.

## Can I do something like this as well?

Sure, check out [CustoPiZer's README](https://github.com/OctoPrint/CustoPiZer) for 
instructions on how to set up your own image build for modified but clean OctoPi images!
