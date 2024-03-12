# FlipIt
Forked from https://github.com/doyou/FlipIt.

Flip Clock Screensaver. Inspired by [Fliqlo](http://fliqlo.com/). Fliqlo on Windows stopped working with a recent (Dec 2015?) Flash update which prompted this project. This project does NOT use Flash.

Improved and fixed some issues:
* Fix redraw when Seconds setting is off.
    *  Default Show Seconds value to false
    *  Switch to use settings value over hard coded value
* Added ARM64 Build


![Screenshot](Screenshot.png)

![Screenshot](WorldTimes.png)

## Requirements

* Microsoft Windows ARM64
* .NET Framework 4.7.2

## Installation

To install without building with Visual Studio, copy the .scr file on the [Releases](https://github.com/tordona/FlipIt/releases) page to:
    * C:\Windows\System32 on 64-bit ARM (ARM64) Windows.

## Building with Visual Studio

Run in Release mode and Run as Administrator to have the build event copy the screensaver to the Windows System32 folder. Set the Command line arguments to `/s` to have the screensaver display full screen on F5/Start.

## Acknowledgements

Source code originally based on the article and code [Creating a Screen Saver with C#](http://www.harding.edu/fmccown/screensaver/screensaver.html) by Frank McCown.

This work is licensed under a [Creative Commons License](http://creativecommons.org/licenses/by-sa/2.0/).
