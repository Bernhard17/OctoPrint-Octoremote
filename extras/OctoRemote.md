---
layout: plugin

id: OctoRemote
title: OctoPrint-Octoremote
description: Control your 3D-Printer with an Arduino and a Keypad or a custom remote
author: Pascal Krumme
license: AGPLv3

date: 2017-03-29

homepage: https://github.com/pkElectronics/OctoPrint-Octoremote
source: https://github.com/pkElectronics/OctoPrint-Octoremote
archive: https://github.com/pkElectronics/OctoPrint-Octoremote/archive/master.zip


# library versions not yet published on PyPi. SHOULD ONLY BE USED IF THERE IS NO OTHER OPTION!
follow_dependency_links: false

# TODO
tags:
- printing
- remote
- arduino
- genuino
- control
- keypad
- remotecontrol
- ui

# TODO
screenshots:
- url: https://github.com/pkElectronics/OctoPrint-Octoremote/doku/Hardware1.JPG
  alt: Arduino with Keypad
  caption: Necessary Components for Version1 Hardware
- url: https://github.com/pkElectronics/OctoPrint-Octoremote/doku/SettingsScreenshot.PNG
  alt: Screenshot of the OctoRemote settings page
  caption: OctoRemote default settings
- url: https://github.com/pkElectronics/OctoPrint-Octoremote/doku/Fritzing.PNG
  alt: Fritzing schematic for Version1 Hardware
  caption: Fritzing schematic
- url: https://github.com/pkElectronics/OctoPrint-Octoremote/doku/Keypad.PNG
  alt: Mapping of the Keypad key to the Octoprint functions
  caption: Key assignment of the 4+4 keypad
  
featuredimage: https://github.com/pkElectronics/OctoPrint-Octoremote/doku/Hardware1.JPG

compatibility:
  # list of compatible versions, for example 1.2.0. If left empty no specific version requirement will be assumed
  octoprint:
  - 1.2.0

  # list of compatible operating systems, valid values are linux, windows, macos, leaving empty defaults to all
  os:
  - linux
  - windows
  - macos
---

**TODO**: OctoRemote enables you to perform all usual printer movements with a simple keypress. Current version implements moving the X-, Y- and Z-Axis, homing and controlling up to four extruders.
Movement distance of the extruders can also be controlled via the keypad. An embedded version of the remote controller is also in the making and will be released soon.