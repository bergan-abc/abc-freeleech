# ABC-Freeleech [![Platform](https://img.shields.io/badge/Platform-win32-red.svg)](https://github.com/bergan-abc/abc-freeleech/releases/tag/v3.3.0.1) [![GitHub release](https://img.shields.io/badge/Release-3.3.0.1-green.svg)](https://github.com/bergan-abc/abc-freeleech/releases/tag/v3.3.0.1) [![Donate](https://img.shields.io/badge/Donate-Paypal-blue.svg)](https://paypal.me/berganabc)

Easily bypass Bittorrent tracker's ratio restrictions.

## What is ABC-Freeleech ?
* It's an efficient "cheating ratio" Bittorrent client.
* Based on LH-ABC by Roee Shlomo ©  2007-2008.
* Written in Python, it currently only runs on MS Windows.
* Ad-free, malware-free, can be used as an everyday Bittorrent Client.
* Requires a License Key to get "Freeleech mode ON".

## What can "Freeleech mode ON" do for me ?
* In can bypass tracker's ratio restrictions.
* Grows artificially your ratio while downloading,
* Or leaves your ratio untouched while downloading.
* Cheat your ratio with ABC-Freeleech's unique stealth methods.

## How to get a License Key ?

Simply send an email to us at **< bergan-abc at protonmail dot com >**, explaining your motivations (don't forget to **join your License Challenge**). We will send back your License Key.

Be warned that License Challenge & License Keys are attached to a computer. They can't be migrated from one computer to another.

<!-- https://wxusy7y79bn183z8.onion/ -->

## Installation

Download [latest release version][1] and start the installer.

## Compatibility

ABC-Freeleech currently runs on:
* Windows 7/8/10 with 32-bit/64-bit architecture.

## Configuration

To fine-tune the Freeleech options, go to File > Preferences.

![ABC-Freeleech GUI](https://raw.githubusercontent.com/bergan-abc/abc-freeleech/master/resources/gui.png)

**NOTICE:** The following options only work with a valid License Key.

* **Download claimed:** is the percentage of the torrent's size that ABC-Freeleech claims to have downloaded from the swarm, to the tracker.
* **Upload claimed:** is the percentage of the torrent's size that ABC-Freelecch claims to have uploaded to the swarm, to the tracker.
* **Left method** (remaining size of torrent to download):
  * **fromtorrentsize:** (torrent size) - (download claimed)
  * **tozero:** (download claimed) * (1 - ((percent of torrent status) / 100))
  * **random:** randomly choose one between the previous ones for each torrent (consistent for a torrent). 

**WARNING:** Do not be too greedy with ABC-Freeleech configuration so as not to be detected.

## Roadmap

* Implement support for magnet links.

## License and Credits

ABC-Freeleech by Bergan Computer, Inc. © 2019-2020. All rights reserved.

It is a derivative work from LH-ABC by Roee Shlomo © 2007-2008 released under the MIT license.

## Disclaimer

This software and the whole package comes without warranty. It may or may not harm your computer. Please use with care. Any damage cannot be related back to the author. The software has been tested on a virtual environment and scanned for viruses and has passed all tests.

  [1]: https://github.com/bergan-abc/abc-freeleech/releases/download/v3.3.0.1/ABC-Freeleech-win32-3.3.0.1.exe