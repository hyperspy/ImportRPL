ImportRPL
=========

Digital Micrograph plugin to import Ripple files

This Digital Micrograph plugin is designed to import Ripple files into Digital Micrograph.
It is used to ease data transit between DigitalMicrograph and [HyperSpy](https://github.com/hyperspy/hyperspy>)
without losing the calibration using the extra keywords that HyperSpy/RosettaSciIO adds to the standard format.

When executed, it will ask for 2 files:

1. The ripple file with the data format and calibrations.
2. The data itself in ``.raw`` format.

If a file with the same name and path as the ripple file exists, which has a
``.raw`` or ``.bin`` extension, it is opened directly without prompting.
