---
layout: guide
categories:
  - arcdps
tags:
  - Addons
  - ArcDPS
  - Guides
author: Xivor
title: ArcDPS EVTC Logging
date: 2020-08-30 02:02:00
description: Record Guild Wars 2 metrics to parse out into easily-readble reports
---

#### What is EVTC Logging?

{{page.title}} is the method ArcDPS uses to {{page.description | downcase}}. There are several settings that are recommended for logging WvW encounters.

![EVTC Logging Options]({{site.url}}/assets/img/addons/image%20%2827%29.png)

#### Boss Encounter Logging Options

###### Save EVTC Logs After Encounter:

This option will output a log onto your local storage for review at a later time. This is required to upload or process using other 3rd party services or software, such as [DPS Report](https://dps.report/). EVTC logs will only work for instanced content, and do not log data for open world PvE.

###### Compress Logs with Powershell (Windows 10)

This option compresses the logs which will save a significant amount of disk space and processing. It is, however, only supported on Windows 10 operating systems.

###### Use NPC Name in EVTC Save Path

This option records the NPC name into the folder structure the logs are saved. This just helps with local organization of files. Not necessary for those that only do WvW and do not do Raids.

###### Use Player Name in EVTC Save Path

This option records the player name into the folder structure the logs are saved. This just helps with local organization of files.

###### Use Guild in EVTC Save Path

This option records the guild name into the folder structure the logs are saved. This just helps with local organization of files.

###### Save EVTC Logs on Squad Combat

This option allows squad combat engagement to trigger the storing of data from ArcDPS.

###### Min Participants for Squad Logs

This option lets you define a minimum amount of participants in combat as the threshold to determine when ArcDPS should start logging data. This can be used to avoid single squad members skirmishing on their own in triggering data logging.

###### Max Participants for Squad Logs

This option lets you define a maximum amount of participants in combat as the threshold to determine when ArcDPS should stop logging data. This is useful if the desired intent is to only log small group data, and not when running with larger zergs.

###### Min Player Enemies for Squad Logs

This option lets you define a minimum amount of enemies in combat as the threshold to determine when ArcDPS should start logging data. This can be used to avoid enemies picking off players as you run by them in triggering logging by ArcDPS.

###### Recommended EVTC Logging for WvW

* Save EVTC Logs After Encounters: **Selected**
* ~~Compress Logs with Powershell (Windows 10): Off~~
* ~~Use NPC Name in EVTC Save Path: Off~~
* Use Player Name in EVTC Save Path: **Selected**
* Use Guild in EVTC Save Path: **Selected**
* Save EVTC Logs on Squad Combat: **Selected**
* Max Participants for Squad Logs: **5**
* Max Participants for Squad Logs: **50**
* Min Player Enemies for Squad Logs: **5**