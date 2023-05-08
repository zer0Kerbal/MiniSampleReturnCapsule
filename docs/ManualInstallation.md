---
permalink: /ManualInstallation.html
title: ManualInstallation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.4.3.0
Mini Sample Return Capsule (MSRC)
created: 04 Aug 2021
updated: 06 May 2023

TEMPLATE: ManualInstallation.md v1.1.9.1
created: 01 Feb 2022
updated: 26 Apr 2023

based upon work by Lisias -->

## [Mini Sample Return Capsule (MSRC)][mod]

[Home](./index.md)

Two size zero (0.625m) parts that make up an autonomous return capsule to stuff your experiments in for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `<MiniSampleReturnCapsule>` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/MiniSampleReturnCapsule`
* Extract the package's `MiniSampleReturnCapsule/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/MiniSampleReturnCapsule` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/MiniSampleReturnCapsule`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/MiniSampleReturnCapsule`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/MiniSampleReturnCapsule`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [MiniSampleReturnCapsule]
      + [Assets]
        ...
      + [Compatibility]
        ...
      + [Config]
        ...
      + [Localization]
        ...
      + [Parts]
        ...
      * #.#.#.#.htm
      * Attributions.htm
      * changelog.md
      * ManualInstallation.htm
      * MiniSampleReturnCapsule.version
      * readme.htm
      * SimpleBSD.txt
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none

THIS FILE: CC BY-ND 4.0 by [zer0Kerbal](https://github.com/zer0Kerbal)
  used with express permission from zer0Kerbal

[mod]: https://www.curseforge.com/kerbal/ksp-mods/MiniSampleReturnCapsule "Mini Sample Return Capsule (MSRC)"