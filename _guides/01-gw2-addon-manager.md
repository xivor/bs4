---
layout: guide
categories: addons
tags:
  - Addons
  - ArcDPS
  - Guides
author: Xivor
pre-title:
title: GW2 Addon Manager
tagline: Addon Management Utility
updated: September 19, 2020
description: Simplifies the process of managing third-party utilities for Guild Wars 2
---

## What is {{page.title}}?

[{{page.title}}](https://github.com/fmmmlee/GW2-Addon-Manager) (also called GW2-UOAOM) is a third-party software application that is used to {{page.description | downcase}}.<!--more--> It is a tool to improve the experience of using addons and plugins in Guild Wars 2 by handling installation, updates, and file management behind the scenes.

![GW2-UOAOM Menu]({{ site.url }}/{{ site.baseurl }}/assets/img/addons/image%20%2838%29.png){:width="800px"}

## Pre-Installation Checklist

Make sure the following items are validated prior to installation.

* Microsoft Windows is required
* .NET Framework (version 4.x and later - should be already installed if using Windows 10)
* Remove any previously-installed add-ons that use plugins to load with Guild Wars 2, such as ArcDPS, GW2Radial, or d912pxy

## Installation

1. Download the [latest stable release](https://github.com/fmmmlee/GW2-Addon-Manager/releases)
2. Extract the zip file to any location you like
3. Right click on "GW2 Addon Manager.exe" do one of the following:
   * Send to Desktop (shortcut)
   * Pin to Start
   * Pin to Quick Access
4. Run shortcut you created or the "GW2 Addon Manager.exe" executable

## Configuration

Note that the program won't work while GW2 or the GW2 launcher is running, as it needs to access and modify files that are locked while the game is active.

* Make sure that the game path is set correctly (the default is C:\Program Files\Guild Wars 2)
* Select the addons you want to install using the checkboxes and click the large UPDATE button on the lower right
* The next time you launch GW2, the addons you selected should be active!

## Additional Configuration Options

![Configuration Options menu]({{ site.url }}/{{ site.baseurl }}/assets/img/addons/image.png)

###### Set Default

Set Default stores the currently selected Add-On's as default. They will stay selected upon each start of the program

###### Delete

Deleting an add-on deletes its plugin and any associated files.

###### Disable

Disabling an add-on moves the plugin out of the game folder and adjusts the other plugin names appropriately.

###### Re-Enable

Enabling a disabled plugin will move it back into the game folder and again rename the plugins to work together (NOTE: hitting "enable" on non-disabled plugins will do nothing).

###### Reset to Clean Install

This does exactly as it sounds. It removes all plugins and allows a fresh install for each.