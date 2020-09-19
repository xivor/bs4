---
layout: guide
categories: addons
tags:
  - Addons
  - ArcDPS
  - Guides
author:
pre-title:
title: ArcDPS
tagline: Damage Meter
updated: September 19, 2020
description: >-
  Enhanced your competitive gaming experience with on-the-fly and recorded
  gaming metrics
---

## What is ArcDPS?

[ArcDPS](https://www.deltaconnected.com/arcdps/) is a third-party software application that is used to {{page.description | downcase}} for Guild Wars 2.<!--more--> It allows players within the same party/squad to see current and simulated damage between their fellow players. For information on whether ArcDPS is safe to use, please read the information on ArcDPS and ArenaNet's position located [here](arcdps-and-arenanet.md).

![Example of ArcDPS in action]({{ site.url }}/{{ site.baseurl }} /assets/img/addons/arcdps-action.gif)

## Installation

This piece of documentation goes over the easiest and most concise method of installing [ArcDPS](https://www.deltaconnected.com/arcdps/) and maintaining an updated installation. This method uses an additional 3rd party utility called [The GW2 Unofficial Addon Manager](https://github.com/fmmmlee/GW2-Addon-Manager)(GW2-UOAOM).

Make sure that Guild Wars 2 is not running at the time of installation. For ArcDPS to function, the only addon needed is the first one, **ArcDPS**. There are many other addons available for install with this utility, but will not cover those in this guide.

1. Make sure that the game path is set correctly (the default is C:\Program Files\Guild Wars 2)
2. Select the **ArcDPS** add-on (ignore any other addons at this time, as they are unnecessary for ArcDPS operation)
3. Click the large **UPDATE** button on the lower right
4. At this time, **GW2-UOAOM** will download and install the latest version of **ArcDPS**.

![Select only the ArcDPS option]({{ site.url }}/{{ site.baseurl }} /assets/img/addons/addon-manager-example-1.png)

## Usage

Use **Alt+Shift+T** to access the ArcDPS options menu.

Overall the user interface is quite straight forward. It displays your current damage, along with your squad/party if you happen to be in one. See the contents menu to the right for guides on creating customized windows for tracking combat statistics in WvW.

## Logging

ArcDPS can log each battle encounter that your character engages in. To do so, logging must be enabled through the options menu. It is suggested to turn on Windows 10 compression if possible, as these log files can be extremely large.

## Reading your logs

Once a log is created it will be saved to C:/Documents/Guild Wars 2/addons/arcdps/arcdps.cbtlogs. These logs are saved in the EVTC format, and may be zipped if compression is enabled.

Reading EVTC logs require a 3rd party parser. The following tools are recommended for reading EVTC logs.

* [DPS.Report](https://dps.report/) - Website that allows for ArcDPS log uploads and parses the data into a human readable format with data sorting into tabs and charts.
* [ArcDPS Log Manager](https://gw2scratch.com/tools/manager) - Software utility that manages ArcDPS logs, gives a snapshot of the group composition data, and contains an integrated upload utility to DPS.Report.