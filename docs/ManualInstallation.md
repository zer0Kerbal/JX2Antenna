---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.0
JX2 Antenna (JX2)
created: 01 Oct 2019
updated: 21 Jul 2022 -->

<!-- based upon work by Lisias -->

# JX2 Antenna (JX2)

[Home](./index.md)

Provides a set of deployable antennas with very high power, up to 1000G, suitable for working with modded (larger) solar systems. For Kerbal Space Program

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `JX2Antenna` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/JX2Antenna`
* Extract the package's `JX2Antenna/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/JX2Antenna` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/JX2Antenna`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/JX2Antenna`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/JX2Antenna`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [JX2Antenna]
      + [Agencies]
        ...
      + [Compatibility]
        ...
      + [Contracts]
        ...
      + [Flags]
        ...
      + [Localization]
        ...
      + [Parts]
        ...
      * #.#.#.#.htm
      * Attributions.htm
      * CC-BY-NC-SA-4.0.txt
      * changelog.md
        ManualInstallation.htm
      * readme.htm
      * JX2Antenna.version
    ...
  * KSP.log
  ...
```

### Dependencies

* none
