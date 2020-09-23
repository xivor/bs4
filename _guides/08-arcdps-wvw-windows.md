---
layout: guide
categories: arcdps
tags:
  - Addons
  - ArcDPS
  - Guides
author: Xivor
pre-title:
title: ArcDPS
tagline: Windows 
updated: September 19, 2020
description: Monitor the live group metrics of the battle in Guild Wars 2
---

## What are the {{page.title}}?

The {{page.title}} are where the user can {{page.description | downcase}}.<!--more-->  These configurations are specific to customizing the display of the {{page.title}} for WvW encounters. 


## Area Stats

The **Areas stats [+] window** will display the raw current statistics for you and your party/squad-group/squad respectively. If in a large squad, these numbers can swap sporadically as large numbers of people handle different targets in different areas. 

The default configuration displays raw damage output. This displays the real-time damage-per-second and total damage for a battle. The information that is displayed from right to left is as follows:

![Area Stats window]({{ site.url }}{{ site.baseurl }}/assets/img/addons/image%20%2831%29.png)

##  Area Stats Window Components

The bar will display (in order from left to right):

* Rank in Squad
* Profession 
* Player Name 
* Player Total Damage
* Damage Per Second
* Percentage of squad total damage

## Area Stats Window Display Configuration

The **Area Stats** window can be customized with a variety of special configurations that can display levels and types of combat statistics.

![]({{ site.url }}{{ site.baseurl }}/assets/img/addons/image%20%287%29.png)

Right click on the Damage window to find the Display menu. Here is where we configure the settings for the way the window appears.

* **Combat Time:** Select this option to show the amount of time a player has been in combat after their name
* **Draw Bars:** Select this option to show the colored bars for each player.  The width of these bars give a visual representation of the player's class and their damage in relation to their group mates.
* **Bar Color by Subgroup:** Select this option if you wish the bar colors to match the members of each subgroup rather than profession
* **Index  Numbers:** Select this option to show the number (1:) in front of the player. This is an unnecessary item and only has use for easy identification of group member.
* **Profession:** Select this option to display the profession before the player name
* **Max Name Length**: Choose the amount of characters you wish to display in the window before the name gets cut off.  **0** allows for the whole name, regardless of character count.
* **Max Displayed**: Unknown and untested at this time.  Leave default.
* **Stats Format:** Set the parameters for what you wish to display on the player bar:
* **Title Bar Format:** Set the parameters for what you wish to display on the title bar. 

## Specialty Windows

The **Area Stats** window is highly customizable and also allows for multiple instances of the window in order to track different data. Some recommended window configurations for WvW using the **Area Stats** window are listed below.

* [Squad Damage Out]({% link _guides/09-arcdps-damage-out-window.md %})
* [Squad Damage Taken]({{10-arcdps-damage-taken-window}})
* [Squad Average DPS]({{11-arcdps-average-dp-windows}})
* [Squad Cleanses]({{14-arcdps-squad-cleanses-window}})
* [Squad Boon Strips]({{12-arcdps-boon-strips-window}})

## Buffs Window

The **Buffs window** will display which and how many buffs players are receiving. By default, this involves buffs they are receiving and putting out. This is a confusing window and it is recommended to not use it.

![Buffs window]({{ site.url }}{{ site.baseurl }}/assets/img/addons/image%20%2826%29.png)

## Buff's Window Components

The bar will display (in order from left to right):

* **Rank**
* **Profession**
* **Player Name**
* **Boon Type**
* **Boon Value** 
  * Displays total seconds the boon would be active for among all players it was applied to
  * Boon strips and conversions cannot be predicted and will not be factored in until they occur

##  Self Stats Window

 The **Self Stats window** will display stats that you are outputting in a minimalistic window.   

![Self Stats window]({{ site.url }}{{ site.baseurl }}/assets/img/addons/image%20%2825%29.png)

## Self Stats Window Components

The window will display three columns (in order from left to right):

* **Stat** (Example – damage, healing, barrier)
* **Target Stats** (Example – 361 DPS)
  * These stats are related to the direct target only. If there is only 1 target this will be the same as the cleave damage below.
  * Hovering over these stats will display the total number of stats and duration of the combat. (Example – 2,228 damage over 6.16 seconds)
* **Cleave Stats** (Example – 361 DPS)
  * These stats are related to the primary target and additional targets. These numbers will ideally be higher with additional party members to heal and additional enemies to cleave.
  * Hovering over these stats will display the total number of stats and duration of the combat. (Example – 2,228 damage over 6.16 seconds)

## Self Skills Window

The **Self Skills window** will display a chart of your damage sources. This window is very helpful for determining the effectiveness of your damage sources and can help you identify the effectiveness of a build and its intended damage.

![Self Skills window](https://flamesofthemist.com/wp-content/uploads/2018/12/arcdps_selfskills.png)

## Self Skills Window Components

The chart will display four columns (in order from left to right):

* **Rank** (most damaging source)
* **Skill/Effect Name** (Example – Orb of Wrath)
* **Total Damage** (Example – 1,070)
* **Percentage of Total Damage** (Example – 47.2%)

In addition to sources, bars behind the text help visually identify the scale of effectiveness between abilities. Rank 1 will typically be a full bar as the most effective ability with the other bars as a percentage of that bar’s effective damage. In the above example, **Orb of Wrath's**  damage was the highest damage at 47.2%, the bar displays as 100%.  **Symbol of Punishment's** damage was at 25.8%, which is close to half of **Orb of Wrath's** damage. Therefore the bar reflects **Symbol of Punishment's** damage in relation to the top skill. 

## Self Skills Window Tooltips

Hovering over any attack/effect name will give you specific numbers to the targets.

* **Hits (cmprs):** The simplistic number of times this skill was cast.
* **Hits (dmg)**: The amount of targets/times this attack successfully landed, which will factor in if a single cast hits multiple targets or hits multiple times.
* **Hits (all):** The amount of targets/times this attack could have landed and can be cut short by target removal, cancellation, downed state, etc.
* **Damage Stats:** These numbers break down basic stats of the attack as a singular entity.

## Metrics Window

The **Metrics window** shows your Frames Per Second (FPS) \[F\], Ping \[P\], and Refresh Rate \[R\].

![Metrics window](https://flamesofthemist.com/wp-content/uploads/2018/12/arcdps_metrics.jpg)

## Metrics Window Components

* **F: Frames per Second** (Example – 95)
  * FPS is essentially how many frames the game is attempting to push to your monitor. The higher the number the smoother your experience will be. 
* **P: Ping** (Example – 37)
  * Ping is a measure in milliseconds it takes to send and receive a response from the server. Low numbers are desirable with anything above 100 being considered moderate and anything above 250 being considered poor.
* **R**: **Refresh Rate** (Example – 26).
  * The lower the number, the worse your response time is between the combat report and server ticks. A low number could cause combat damage to be calculated incorrectly to “real time” and can also effect ArcDPS directly in its reporting. 

## Logs Window

The **Logs window** shows advanced information in a similar manner as the standard Guild Wars 2 combat log.

![Logs window](https://flamesofthemist.com/wp-content/uploads/2018/12/arcdps_log.jpg)

## Health Bar

The **Health Bar** displays a number that is attached to the standard enemy health bars in the top-middle of the screen. It will display a number of up to 2 decimal places for better representation of the amount of health remaining on an enemy.

![Health Bar](https://flamesofthemist.com/wp-content/uploads/2018/12/arcdps_healthbar.jpg)



