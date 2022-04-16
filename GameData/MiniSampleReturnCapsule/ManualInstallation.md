---
permalink: /ManualInstallation.html
title: ManualInstallation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
# layout: bare
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.5.0
Mini Sample Return Capsule (MSRC)
created: 01 Oct 2019
updated: 11 Apr 2022 -->

<!-- based upon work by Lisias -->

# Mini Sample Return Capsule (MSRC)

[Home](./index.md)

Two size zero (0.625m) parts that make up an autonomous return capsule to stuff your experiments in for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the MiniSampleReturnCapsule folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/MiniSampleReturnCapsule`
* Extract the package's `MiniSampleReturnCapsule/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/MiniSampleReturnCapsule` --> `<KSP_ROOT>/GameData/MiniSampleReturnCapsule`
    * Overwrite any preexisting folder/file(s).

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/MiniSampleReturnCapsule`
* Extract the package's `GameData/MiniSampleReturnCapsule` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData/MiniSampleReturnCapsule` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting file.

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [MiniSampleReturnCapsule]
      + [Assets]
        ...
      + [Compatibility]
        ...
      + [Localization]
        ...
      + [Parts]
        ...
      * #.#.#.#.htm
      * changelog.md
      * SimpleBSD.txt
      * readme.htm
      * MiniSampleReturnCapsule.version
    ...
  * KSP.log
  ...
```

### Dependencies

* none
