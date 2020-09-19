---
layout: guide
categories: addons
tags:
  - Addons
  - ArcDPS
  - Guides
author: Xivor
title: ArcDPS Log Manager 
updated: September 19, 2020
description: Maintain and review ArcDPS combat logs and easily upload them to the web
---

## What is {{page.title}}?

[{{page.title}}](https://gw2scratch.com/tools/manager) is a third-party application that is used to {{page.description}}.<!--more--> This utility gives a snapshot ArcDPS Log information and contains an integrated upload utility to [DPS.Report](https://dps.report).

![ArcDPS Log Manager]({{ site.url }}/{{ site.baseurl }} /assets/img/addons/image%20%2830%29.png)

## Installation

There is no installation executable. To use, follow the steps below:

1. Download the [latest release](https://github.com/gw2scratch/evtc/releases).
2. Extract to the location of your choosing.
3. Run the executable.

## Configuration

1. Navigate to Settings
2. In the Logs tab, set the log directory that matches the directory ArcDPS stores logs. Default is **C:\\Users\\USER\_HERE\\Documents\\Guild Wars 2\\addons\\arcdps\\arcdps.cbtlogs.**
3. Navigate to the Guild Wars 2 API Key tab and select the option to **Use the Guild Wars 2 API**.
4. Save

## Usage

###### Logs Tab

* Click on an encounter to view information to the right of participants in the group.
* Right-click on any encounter to customize the headers displayed.
* Highlight an encounter and press the **Upload to dps.report (EI)** button to upload the log to the DPS.Report perser and generate a report link in the text field below the button.
* Click **Open** to review the parsed combat log on the DPS.Report website.

###### Players Tab

* Click on a player to display only the logs that player has been recorded in and on what characters.
* Filter by character or account name as needed.
* Logs for just that player can then be viewed in a separate window.

###### Guilds Tab

* Click on a guild to display player accounts and characters from that guild.
* Filter by guild name or member name as needed.
* Logs for just this guild can then be viewed in a separate window.

###### Statistics Tab

* **Encounters:** Displays statistics on each specific boss/encounter. WvW only players will only see **World Versus World**.
* **Specializations:** Displays statistics on professions and specializations that have been recorded.