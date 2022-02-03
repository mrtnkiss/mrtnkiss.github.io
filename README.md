# PetTracker Update - 9.1 Pets

## Summary

There is an open issue for the missing Maw / Korthia pets in PetTracker Addon - [https://github.com/Jaliborc/PetTracker/issues/266](https://github.com/Jaliborc/PetTracker/issues/266)

I've started compiling the pets, and where they are found, and attached is a data file with the updates. The Data file is based on the 9.1.2 version as of 2022-02-03.

Pets which are included in the updated data file are those from the following table which have mapped coordinates. Coordinates currently are "raw", meaning they are not clustered, there are a lot of coords in a small radius. Also, I haven't looked into if it is possible to add "conditional" coordinates, e.g.: only show pets on the map when the appropriate Maw Assault is going on. Anyhow, this is a start, I'll look into the clustering issue if it can be fixed. 

## Screenshots

[<img src="Images/korthia.jpg" width=400>](Images/korthia.jpg)[<img src="Images/oribos.jpg" width=400>](Images/oribos.jpg)

## Instructions

Replace existing "Interface\AddOns\PetTracker\addons\main\api\data.lua" file with the attached data file: [data.lua](Data/data.lua)

Have fun collecting the pets!

## Table

| ID   | Battle Pet URL                                               | Companion URL                                                | Source                                  | Have coordinates |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | --------------------------------------- | ---------------- |
| 3100 | [Timeless   Mechanical Dragonling](https://www.wowhead.com/npc=179125/) | [Timeless Mechanical Dragonling](https://www.wowhead.com/item=186556/timeless-mechanical-dragonling) | Anniversary Reward                      |                  |
| 3107 | [Gurgl](https://www.wowhead.com/npc=179140/)                 | [Gurgl](https://www.wowhead.com/item=186553/gurgl)           | Dalaran - Quest                         |                  |
| 3092 | [Squibbles](https://www.wowhead.com/npc=176662/)             | [Squibbles](https://www.wowhead.com/item=184867/squibbles)   | Kun'Lai Summit - Rival Anthea           |                  |
| 3153 | [Blinky](https://www.wowhead.com/npc=179589/)                |                                                              | In Game Shop                            |                  |
| 3102 | [Animite Broodling](https://www.wowhead.com/npc=179131/)     |                                                              | Korthia - Battle                        | Yes              |
| 3134 | [Anxious Nibbler](https://www.wowhead.com/npc=179248/)       |                                                              | Korthia - Battle                        | Yes              |
| 3139 | [Devourling](https://www.wowhead.com/npc=179256/)            |                                                              | Korthia - Battle                        | Yes              |
| 3141 | [Wild Corpsefly](https://www.wowhead.com/npc=179329/)        |                                                              | Korthia - Battle                        | Yes              |
| 3135 | [Young   Garnetgullet](https://www.wowhead.com/npc=179250/)  |                                                              | Korthia - Battle                        | Yes              |
| 3136 | [Korthian Specimen](https://www.wowhead.com/npc=179251/)     | [Korthian   Specimen](https://www.wowhead.com/item=186542/korthian-specimen) | Korthia - Rare Drop                     | Yes              |
| 3127 | [Chompy](https://www.wowhead.com/npc=179230/)                | [Chompy](https://www.wowhead.com/item=186548/chompy)         | Korthia - Quest Reward                  |                  |
| 3138 | [Domestic Aunian](https://www.wowhead.com/npc=179253/)       | [Domestic   Aunian](https://www.wowhead.com/item=186543/domestic-aunian) | Korthia - Vendor                        | Yes              |
| 3097 | [Flawless Amethyst   Baubleworm](https://www.wowhead.com/npc=178216/) | [Flawless Amethyst Baubleworm](https://www.wowhead.com/item=185919/flawless-amethyst-baubleworm) | Oribos - Vendor                         | Yes              |
| 3104 | [Ruby Baubleworm](https://www.wowhead.com/npc=179137/)       | [Ruby   Baubleworm](https://www.wowhead.com/item=186537/ruby-baubleworm) | Oribos - Vendor                         | Yes              |
| 3106 | [Topaz Baubleworm](https://www.wowhead.com/npc=179139/)      | [Topaz   Baubleworm](https://www.wowhead.com/item=186535/topaz-baubleworm) | Oribos - Vendor                         | Yes              |
| 3105 | [Turquoise   Baubleworm](https://www.wowhead.com/npc=179138/) | [Turquoise Baubleworm](https://www.wowhead.com/item=186536/turquoise-baubleworm) | Oribos - Vendor                         | Yes              |
| 3137 | [Mosscoated Gromit](https://www.wowhead.com/npc=179252/)     | [Mosscoated   Hopper](https://www.wowhead.com/item=186541/mosscoated-hopper) | Paragon Reward - Death's Advance        |                  |
| 3140 | [Gnashtooth](https://www.wowhead.com/npc=179255/)            | [Gnashtooth](https://www.wowhead.com/item=186538/gnashtooth) | Paragon Reward - The  Archivists' Codex |                  |
| 3133 | [Rook](https://www.wowhead.com/npc=179242/)                  | [Rook](https://www.wowhead.com/item=186552/rook)             | Paragon Reward - Ve'nari                |                  |
| 3128 | [Eye of Allseeing](https://www.wowhead.com/npc=179232/)      | [Eye   of Allseeing](https://www.wowhead.com/item=186554/eye-of-allseeing) | Sanctum of Domination -  Raid Drop      |                  |
| 3129 | [Eye of   Extermination](https://www.wowhead.com/npc=179233/) | [Eye of Extermination](https://www.wowhead.com/item=186555/eye-of-extermination) | Sanctum of Domination - Raid Drop       |                  |
| 3122 | [Irongrasp](https://www.wowhead.com/npc=179222/)             | [Irongrasp](https://www.wowhead.com/item=186558/irongrasp)   | Sanctum of Domination -  Raid Drop      |                  |
| 3131 | [Mawsworn Minion](https://www.wowhead.com/npc=179240/)       | [Mawsworn   Minion](https://www.wowhead.com/item=186550/mawsworn-minion) | Sanctum of Domination - Raid Drop       |                  |
| 3108 | [Curious Purrkin](https://www.wowhead.com/npc=179164/)       |                                                              | Tazavesh - Battle                       | Yes              |
| 3111 | [Damp Skrat](https://www.wowhead.com/npc=179167/)            |                                                              | Tazavesh - Battle                       | Yes              |
| 3112 | [Scavenging Skrat](https://www.wowhead.com/npc=179168/)      |                                                              | Tazavesh - Battle                       | Yes              |
| 3109 | [Silver Purrkin](https://www.wowhead.com/npc=179165/)        |                                                              | Tazavesh - Battle                       | Yes              |
| 3110 | [Gizmo](https://www.wowhead.com/npc=179166/)                 | [Gizmo](https://www.wowhead.com/item=186534/gizmo)           | Tazavesh - Boss Drop                    | Yes              |
| 3113 | [Rarity](https://www.wowhead.com/npc=179169/)                | [Rarity](https://www.wowhead.com/item=186540/rarity)         | Tazavesh - Secret Vendor                | Yes              |
| 3098 | [Lil'Abom](https://www.wowhead.com/npc=179008/)              | [Lil'Abom](https://www.wowhead.com/item=186188/lilabom)      | The Maw - Assault Collect               |                  |
| 3101 | [Sly](https://www.wowhead.com/npc=179083/)                   | [Sly](https://www.wowhead.com/item=186539/sly)               | The Maw - Assault Collect               |                  |
| 3103 | [Copperback   Etherwyrm](https://www.wowhead.com/npc=179132/) | [Copperback Etherwyrm](https://www.wowhead.com/item=186546/copperback-etherwyrm) | The Maw - Assault Reward                |                  |
| 3114 | [Fodder](https://www.wowhead.com/npc=179171/)                | [Fodder](https://www.wowhead.com/item=186557/fodder)         | The Maw - Assault Reward                |                  |
| 3099 | [Infused Etherwyrm](https://www.wowhead.com/npc=179025/)     | [Infused   Etherwyrm](https://www.wowhead.com/item=186191/infused-etherwyrm) | The Maw - Assault Reward                |                  |
| 3116 | [Invasive Buzzer](https://www.wowhead.com/npc=179180/)       | [Invasive   Buzzer](https://www.wowhead.com/item=186547/invasive-buzzer) | The Maw - Assault Reward                |                  |
| 3115 | [Clinging Remains](https://www.wowhead.com/npc=179179/)      |                                                              | The Maw - Battle                        | Yes              |
| 3123 | [Deathroach](https://www.wowhead.com/npc=179226/)            |                                                              | The Maw - Battle                        | Yes              |
| 3126 | [Eye of Affliction](https://www.wowhead.com/npc=179229/)     |                                                              | The Maw - Battle                        | Yes              |
| 3120 | [Grip of Terror](https://www.wowhead.com/npc=179219/)        |                                                              | The Maw - Battle                        | Yes              |
| 3119 | [Lost Limb](https://www.wowhead.com/npc=179183/)             |                                                              | The Maw - Battle                        | Yes              |
| 3118 | [Scurrying Mawrat](https://www.wowhead.com/npc=179182/)      |                                                              | The Maw - Battle                        | Yes              |
| 3124 | [Vile Deathroach](https://www.wowhead.com/npc=179227/)       |                                                              | The Maw - Battle                        | Yes              |
| 3125 | [Golden Eye](https://www.wowhead.com/npc=179228/)            | [Golden   Eye](https://www.wowhead.com/item=186564/golden-eye) | The Maw - Drop                          | Yes              |
| 3121 | [Grappling   Gauntlet](https://www.wowhead.com/npc=179220/)  | [Grappling   Gauntlet](https://www.wowhead.com/item=186559/grappling-gauntlet) | The Maw - Drop                          |                  |
| 3117 | [Amaranthine   Stinger](https://www.wowhead.com/npc=179181/) | [Amaranthine Stinger](https://www.wowhead.com/item=186449/amaranthine-stinger) | The Maw - Tormentor Drop                | Yes              |
| 3132 | [Mord'al   Eveningstar](https://www.wowhead.com/npc=179241/) | [Mord'al   Eveningstar](https://www.wowhead.com/item=186551/mordal-eveningstar) | Torghast - Achievement                  |                  |
| 3130 | [Gilded Darknight](https://www.wowhead.com/npc=179239/)      | [Gilded   Darknight](https://www.wowhead.com/item=186549/gilded-darknight) | Torghast - Adamant Vaults Drop          |                  |
