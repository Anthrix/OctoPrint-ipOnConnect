# OctoPrint-ipOnConnect

A simple plugin to send an M117 (Default)/M70 (Optional setting) command to show the connected OctoPrint's IP address information on the printer's display.

![screenshot](screenshot.jpg)

# Setup

Install via the bundled [Plugin Manager](https://github.com/foosel/OctoPrint/wiki/Plugin:-Plugin-Manager)
or manually using this URL:

    https://github.com/jneilliii/OctoPrint-ipOnConnect/archive/master.zip

# Changelog

## [0.2.3] - 2019-10-03
### Added
- Python 3 compatibility.

## [0.2.2] - 2019-04-08
### Added
- Optional parameter in settings to enable the use of M70 command instead of M117 for Sailfish firmware thanks to @ohrn.

## [0.2.1] - 2018-11-17
### Added
- New `Include Trailing Character` setting to account for some firmware that clips the last character of M117 commands (i.e. ANET E10).

## [0.2.0] - 2018-05-26
### Added
- New delay option for checking ip and sending to control panel to resolve cold start issues.
- Settings interface to set delay option mentioned above.
- Added ConnectivityChanged event monitoring to also trigger the ip check and display.

### Changed
- Uses the Connectivity check settings for ip and port to attempt to make connection to those for determining ip address being used.

## [0.1.0] - 2016-09-24
### Added
- Initial release.

# Support My Efforts
I programmed this plugin for fun and do my best effort to support those that have issues with it, please return the favor and support me.

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://paypal.me/jneilliii)

[0.2.3]: https://github.com/jneilliii/OctoPrint-ipOnConnect/tree/0.2.3
[0.2.2]: https://github.com/jneilliii/OctoPrint-ipOnConnect/tree/0.2.2
[0.2.1]: https://github.com/jneilliii/OctoPrint-ipOnConnect/tree/0.2.1
[0.2.0]: https://github.com/jneilliii/OctoPrint-ipOnConnect/tree/0.2.0
[0.1.0]: https://github.com/jneilliii/OctoPrint-ipOnConnect/tree/0.1.0

