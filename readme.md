TXOnlySerial
========

[![License: LGPL v3](https://img.shields.io/badge/License-LGPLv3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)
[![Installation instructions](https://www.ardu-badge.com/badge/TXOnlySerial.svg?)](https://www.ardu-badge.com/TXOnlySerial)
[![Commits since latest](https://img.shields.io/github/commits-since/felias-fogg/TXOnlySerial/latest?include_prereleases)](https://github.com/felias-fogg/TXOnlySerial/commits/master)
![Hit Counter](https://visitor-badge.laobi.icu/badge?page_id=felias-fogg_TXOnlySerial)
[![Build Status](https://github.com/felias-fogg/TXOnlySerial/workflows/LibraryBuild/badge.svg)](https://github.com/felias-fogg/TXOnlySerial/actions)

This is a transmit-only serial library, which is software driven (bit-banging). In fact, it has been derived from the SoftwareSerial library by simply deleting all the receive methods (including the interrupt handling). It is very useful, when you want to get some debug output, for instance. It uses just one pin, which can be freely defined and it uses less memory than the SoftwareSerial library. Compared to SoftwareSerial, you save roughly 900 bytes flash and 80 bytes RAM.

Usage is very similar to SoftwareSerial, except that you use only one argument when creating an object, namely, the TX pin.

