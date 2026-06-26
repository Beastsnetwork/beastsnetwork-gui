# Beastsnetwork GUI Wallet Windows Installer

Copyright (c) 2017-2024, The Beastsnetwork Project

## Introduction

This is a *Inno Setup* script `Beastsnetwork.iss` plus some related files that allows you to build a standalone Windows installer (.exe) for the GUI wallet.

This turns the GUI wallet into a more or less standard Windows program, by default installed into a subdirectory of `C:\Program Files`, a program group with some icons in the *Start* menu, and automatic uninstall support.

## License

See [LICENSE](LICENSE).

## Building

You can only build on Windows, and the result is always a Windows .exe file that can act as a standalone installer for the GUI wallet.

The build steps in detail:

1. Install *Inno Setup*. You can get it from [here](http://www.jrsoftware.org/isdl.php)
2. Get the Inno Setup script plus related files by cloning the whole [beastsnetwork-gui GitHub repository](https://github.com/Beastsnetwork/beastsnetwork-gui); you will only need the files in the installer directory `installers\windows` however.
3. The setup script is written to take the GUI wallet files from a subdirectory named `bin`; so create `installers\windows\bin`, get the zip file of the GUI wallet from [here](https://beastsnetwork.win/downloads/), unpack it somewhere, and copy all the files and subdirectories in the single subdirectory there to this `bin` subdirectory
4. Start Inno Setup, load `Beastsnetwork.iss` and compile it
5. The result (the finished installer) will be the file `mysetup.exe` in the `installers\windows\Output` subdirectory
