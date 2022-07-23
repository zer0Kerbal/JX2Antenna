---
permalink: /Changelog.html
title: The Change Log
description: The Opening Credits, and the closing credits, plus the first of two (or is three) end credit scenes
tags: changes,changelog,change-log,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- 
hdr-changelog.md v1.0.0.0
JX2 Antenna (JX2)
created: 13 May 2022
updated:
CC BY-ND 4.0 by zer0Kerbal
--># Changelog  
  
| modName    | JX2 Antenna (JX2)                                                 |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-SA-4.0                                                      |
| author     | steedcrugeon, Snark and zer0Kerbal                                |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/153125-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/JX2Antenna)             |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/JX2Antenna)           |
| spacedock  | (https://spacedock.info/mod/1107)                                 |
| ckan       | JX2Antenna                                                        |

## Version 2.0.99.0-adoption - `<Fine Tuned>` edition

* 21 Jul 2022
* Released for Kerbal Space Program 1.12.3

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts/

### Parts

* Add
  * [DRAG_CUBES]
  * @thumbs
  * [PhysicsSignificance] = 1

#### ModuleCargoPart

| JX2Antenna |         |       | π╥     | πr²h       | 1000L = m3 |
| ---------- | ------- | ----- | ------ | ---------- | ---------- |
|            | dia (m) | r (m) | h (m)  | volume m^3 | *1000      |
| ju1MDA     | 1.25    | 0.625 | 2.5900 | 3.17841    | 3178.41    |
| jw1MDA     | 1.25    | 0.625 | 1.0900 | 1.33763    | 1337.64    |
| jx2LDA     | 2.5     | 1.25  | 4.1500 | 20.37126   | 20371.27   |

* [ju1MDA.cfg]
  * Dimensions = x: 1.25, y: 2.59, z: 1.28
  * [ModuleCargoPart] = 4500
* [jw1MDA.cfg]
  * Dimensions = x: 1.24, y: 1.09, z: 1.29
  * [ModuleCargoPart] = 1400
* [jx2LDA.cfg]
  * Dimensions = x: 2.48, y: 4.15, z: 2.48
  * [ModuleCargoPart] = 22000
* closes #46 - Update Parts

### docs/

* Add
  * [Attribution.md] v1.0.6.0
  * [ManualInstallation.md] v1.1.7.0
  * [404.md] v1.0.3.1
  * [LegalMumboJumbo.md] v1.0.5.0
  * [Localizations.md] v1.1.3.1
  * [Marketing.md] v1.0.0.0
  * [Notices.md] v1.0.0.0
  * [Part-Catelog.md] v1.1.4.0
  * [Why.md] v1.1.0.0
  * [_config.yml]

### documentation

* [JX2Antenna.version]
  * remove [KSP_VERSION_MAX]

### Localization

* Create
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
* closes #10 - English <us-en.cfg>
* closes #27 - Part Localization
* updates #9 - Localization - Master

### Compatibility

* [GalileosPlanetPack.cfg] v1.0.0.0
  * rename from [jx2_GPP.cfg]
  * add :NEEDS[GPP]
* [IndicatorLights.cfg] v1.0.0.0
  * rename from [jx2_IndicatorLights.cfg]
  * add :NEEDS[IndicatorLights]
* [OuterPlanetsMod.cfg] v1.0.0.0
  * rename from [jx2_OPM.cfg]
  * add :NEEDS[OPM,!GEP_CommNet,!Komplexity]
* [RemoteTech.cfg] v1.0.0.0
  * rename from [jx2_RemoteTech.cfg]
  * add :NEEDS[RemoteTech]

### Config

* Create
  * [JX2Antenna.cfg] v1.0.0.0
    * updates tags with localizations

### Status 2.0.99.0

* Issues
  * closes #5 - JX2Antenna (JX2) 2.0.99.0-adoption `<Fine Tuned>`
  * closes #6 - 2.0.99.0 Verify Legal Mumbo Jumbo
  * closes #7 - 2.0.99.0 Update Documentation
  * closes #8 - 2.0.99.0 Update Social Media

---

## Version 2.0.5.0-release

* 2018-05-10
* Released for Kerbal Space Program 1.12.3

* Update OPM compatibility patch to work with GEP_CommNet. Thanks [OhioBob](https://forum.kerbalspaceprogram.com/index.php?/profile/128005-ohiobob/)!

* Issues
  * closes #35 - 2.0.5.0-release
  * closes #4 - Previous Releases

---

## Version 2.0.4.0-release

* 2018-04-13
* Released for Kerbal Space Program 1.4.2

* Fix the OPM compatibility patch (again)-- it was causing NRE spam for certain other mods.

* Issues
  * closes #34 - 2.0.4.0-release
  * updates #4 - Previous Releases

---

## Version 2.0.3.0-release

* 2018-04-12
* Released for Kerbal Space Program 1.4.2

* Update the OPM patch, since OPM has changed how it handles antenna ranges.
* Thanks to [Benja](https://forum.kerbalspaceprogram.com/index.php?/profile/187938-benja/) for the heads-up!
* DEPRECATED - DO NOT USE this version. Has a bug that breaks some mods. Use 2.0.4.0 or newer.

* Issues
  * closes #33 - 2.0.3.0-release
  * updates #4 - Previous Releases

---

## Version 2.0.2.0-release

* 2017-06-25
* Released for Kerbal Space Program 1.4.2

* Fix a bug in the model files that was causing KSP to hang on ship launch if there are more than one JX2 antenna on the ship.
* Thanks to [Chimichanga](http://forum.kerbalspaceprogram.com/index.php?/profile/144936-chimichanga/) for catching this!

* Issues
  * closes #32 - 2.0.2.0-release
  * updates #4 - Previous Releases

---

## Version 2.0.1.0-release

* 2017-06-18
* Released for Kerbal Space Program 1.3.0

* **DEPRECATED, DO NOT USE**. Has a model bug that causes KSP to hang on vessel launch if there are more than one JX2 on the ship. Bug is fixed in version 2.0.2.
* Fix a bug in the RemoteTech compatibility patch. Thanks to [Starman4308](http://forum.kerbalspaceprogram.com/index.php?/profile/122674-starman4308/) for catching!

* Issues
  * closes #31 - 2.0.1.0-release
  * updates #4 - Previous Releases

---

## Version 2.0.0.0-release

* 2017-06-15
* Released for Kerbal Space Program 1.3.0

* **DEPRECATED, DO NOT USE**. Has a model bug that causes KSP to hang on vessel launch if there are more than one JX2 on the ship. Bug is fixed in version 2.0.2.
* Two new antennas! Meet the [JU1 relay](https://github.com/KSPSnark/JX2Antenna/raw/master/screenshots/JU1MDA.png) and the [JW1 direct](https://github.com/KSPSnark/JX2Antenna/raw/master/screenshots/JW1MDA.png).
* Texture update for the JX2. Twice the flags at no additional cost.
* KSP 1.3 compatibility.

* Issues
  * closes #30 - 2.0.0.0-release
  * updates #4 - Previous Releases

---

## Version 1.1.0.0-release

* 2017-02-09
* Released for Kerbal Space Program 1.3.0

* Add a patch for [Galileo's Planet Pack](http://forum.kerbalspaceprogram.com/index.php?/topic/152136-122-galileos-planet-pack-official-release-v11/).

* Issues
  * closes #29 - 1.1.0.0-release
  * updates #4 - Previous Releases

---

## Version 1.0.0.0-release

* 2016-12-07
* Released for Kerbal Space Program 1.2.2

### Initial release

* Includes JX2 Large Deployable Antenna.
* Includes patch for IndicatorLights.
* Includes patch for RemoteTech.
* Includes patch for OPM.

* Issues
  * closes #28 - 1.0.0.0-release
  * updates #4 - Previous Releases

---

this file: CC-BY-SA-4.0 by zer0Kerbal
