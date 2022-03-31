<!--
changelog.md v1.0.0.0
Mini Sample Return Capsule (MSRC)
this file: GPLv2 BY zer0Kerbal
created: 25 Feb 2020
updated: 01 Feb 2022
-->
# Changelog  
  
| modName    | Mini Sample Return Capsule (MSRC)                                    |
| ---------- | -------------------------------------------------------------------- |
| author     | CobaltWolf, AlbertKermin and zer0Kerbal                              |
| license    | SimpleBSD-2                                                          |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/204186-*)     |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/MiniSampleReturnCapsule)   |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/MiniSampleReturnCapsule) |
| spacedock  | (https://spacedock.info/mod/831)                                     |
| ckan       | MiniSampleReturnCapsule                                              |

## Version 1.4.2.1 - `<Before, For, After>`

### This is PRE-RELEASE - and WILL break saves

* 30 Mar 2022
* Release for Kerbal Space Program [KSP 1.12.3]

### DO A CLEAN INSTALL: DELETE EXISTING THEN RE-INSTALL  

### WARNING: Only [CurseForge][CRSFG:url] version will include .dll’s

### Fixed

* [Kerbalism.cfg] v1.0.1.0
  * Thank you [AmanitaVerna]
  * 'more than one pass specifier detected'
  * removed :FOR[MiniSampleReturnCapsule] and kept :BEFORE/AFTER[KerbalismDefault]
  * concerned that calling KerbalismDefault will tell MM that it is installed.
  * fixes #71 - [Bug 🐞]: Warnings from Module Manager for kerbalism.cfg

### Update

* docs/
* automation
* documentation
* [MiniSampleReturnCapsule.version]
  * removed
    * [KSP_VERSION_MAX]

### Status

* Issues
  * closes #73 Mini Sample Return Capsule 1.4.2.1-release `<NAME>`
  * closes #74 1.4.2.1 Verify Legal Mumbo Jumbo
  * closes #75 1.4.2.1 Update Documentation
  * closes #76 1.4.2.1 Update Social Media
  * closes #71 [Bug 🐞]: Warnings from Module Manager for kerbalism.cfg

---

## Version 1.4.1.0 - Packed and ready to return

* 2021-09-16
* Released for Kerbal Space Program 1.12.2

* DO A CLEAN INSTALL: DELETE EXISTING THEN RE-INSTALL</color></b>

### Update

### 1.4.1.0 Localization

* [Localization\readme.md]
  * to version 2.0.0.0 which closes #7

* created .legal folder with forum adoption approval

### 1.4.1.0 Added

* [kOS.cfg]
  * kOS compatibility
  * +10 [cost]
  * +0.005 [mass]
  * +5 [ElectricCharge]
  * 10000 [diskSpace]
  * 'kOS Processor.' added to [description]
  * [KOSNameTag] = [name] i.e. [msrc-parachute] or [msrc-cargobay]
* [TarsierSpaceTech.cfg]
  * Tarsier Space Tech compatibility
  * +150 [cost]
  * +0.075 [mass]
  * 120 [Capacity]
  * +50 [ElectricCharge]
  * false [fillFromEVA]
  * 'Science HardDrive..' added to [description]
* [RemoteTech.cfg]
  * RemoteTech compatibility
  * 'RemoteTech Enabled.' added to description

### 1.4.1.0 Updated

* [mrsc-cargobay] and [msrc-parachute]
  * [ModuleCargoPart] packedVolume = 125 from 1100 (based upon volume of a column~ish)
  * [ModuleCargoPart] packedVolume = 100 from 1200 (based upon volume of a hemisphere~ish)

### 1.4.1.0 Maintenance

* Incremental Upgrades
  * minor housekeeping
  * linting and duct taping
  * patch dusting (mostly removing construction dust (comments)
  * modernization, polish, update pass on part.cfg's
  * automated back end processes.

### 1.4.1.0 Status

* Issues
  * closes #7 Localization/readme.md
  * closes #10 [ModuleCargoPart] packedVolume seems a tad high
  * closes #14 - back end
  * closes #16 Tarsier Space Tech compatibility
  * closes #17 add kOS compatibility
  * closes #20 add RemoteTech description blurb
  * updated #8 us-en.cfg should be complete

### 1.4.1.0 Possible future changes

* ***❓ ❔ seems high : ❓ ❔***
  * [breakingForce = 50]
  * [breakingTorque = 50] seems high ???
  * [crashTolerance = 12]

* update Localization\readme.md --> 2.0.0.0 which closes #11

---

## Version 1.4.0.0 - Old dog, new tricks

* 2021-08-04
* Released for Kerbal Space Program 1.12.2
* -- Adoption for curation by zer0Kerbal --

* DO A CLEAN INSTALL: DELETE EXISTING THEN RE-INSTALL</color></b>

### 1.4.0.0 Updated

* Restructure folders
  * moved models/textures into /Assets/
  * updated .mu pointers from .tga -> .dds
  * initial Localization push
  * created GitHub Repo
  * created Curseforge page
  * updated SpaceDock
  * renamed GitHub repository to MiniSampleReturnCapsule
  * updated CKAN/NetKAN
  * created new forum thread
  * updated to automated back end processes.
  * automated deploy/release process
  * moved changelog into separate file
  * Changelog.md -> Kerbal Changelog Changelog.cfg
  * created Readme.md
  * added .version file
  * added license file(s)
  * merged in patches
  * linting and duct taping
* Cargo Pass
  * added ModuleCargoPart
* Modernization, polish, update pass on part.cfg's
  * fully updated and modernized all parts
  * added @thumbs

### 1.4.0.0 Localization

* us-en.cfg should be completed
* added localization readme.md
* updated part tags

### 1.4.0.0 Changes

* [mrsc-cargobay]
  * renamed part to [mrsc-cargobay] no _ and all lowercase
  * changed from size1 to size0
  * moved from [Utility] to [Payload]
  * updated [bulkheadProfiles] from size0 to size0
  * added [ModuleCargoPart] packedVolume = 1100 (based upon volume of a column~ish)
  * added [CoPOffset] = 0.0, 0.2, 0.0
  * added [CoLOffset] = 0.0, -0.05, 0.0
  * added [thermalMassModifier] and set it to 5.0 to match stock 1.25m service bay
  * didn't adjust [xxxDrag] because settings match stock 1.25m service bay
  * adjusted [lookupRadius] from 0.9 to 0.4 as suggested by @draqsko
  * added [lookupCenter] = 0.0, 0.1306, 0.0 as suggested by @draqsko
  * added [partTypeName] = Service bay to match stock 1.25m service bay
* [mrsc-parachute]
  * renamed part to [mrsc-parachute] no _ and all lowercase
  * moved [category] to [Pods] from [Utility]
  * added [RSCFX]
  * added [ModuleScienceContainer]
  * added [ModuleDataTransmitter]
  * [ModuleRCS] --> [ModuleRCSFX]
  * added [SASServiceLevel = 1] allows to hold (prograde/retrograde)
  * added [torqueResponseSpeed = 10] to [ModuleReactionWheel]
  * added [hasHibernation, hibernation, hibernateOnWarp, hibernationMultiplier] to [ModuleCommand]
  * adjusted EC consumption form 0.020 -> 0.005 for [ModuleCommand]
  * added [CrewCapacity = 0]
  * adjusted [maxTemp] to 1200 from 2000 to match mk1pod
  * added [skinMaxTemp] = 2200 to match mk1pod
  * added [skinInternalConductionMult] = 0.625 to match mk1pod
  * added [ModuleConductionMultiplier] to match mk1pod
  * added [heatConductivity] = 0.1 to match mk1pod
  * adjusted [maximum_drag] to 0.2 from 0.01
  * adjusted [minimum_drag] to 0.15 from 0.01
  * adjusted [angularDrag] to 1.5 from 0.1
  * added [ModuleCargoPart] packedVolume = 1200 (based upon volume of a sphere~ish)
  * adjusted [ModuleDragModifier][DEPLOYED][dragModifier] to 6 from 24
  * adjusted [ModuleDragModifier][DEPLOYED][dragModifier] to 9 from 6 - landed at just under 10m/s
  * added [explosionPotential] = 0
  * added [buoyancy = 6.0] darn thing refused to float!

### 1.4.0.0 Possible future changes

* Possible future changes
  * [breakingForce = 50] and [breakingTorque = 50] seems high ???

---

## Version 1.3.0.0 - 1.3.0.0

* 2017-03-14
* Released for Kerbal Space Program 1.2.2

### 1.3.0.0 Changes

* Fix for MSRC appearing as debris

---

## Version 1.2.0.0 - 1.2.0.0

* 2016-11-09
* Updated and Released for Kerbal Space Program 1.2.1

### 1.2.0.0 Changes

* Removed reaction wheels from parachute/probe core

---

## Version 1.1.0.0

* 016-07-13
* Released for Kerbal Space Program 1.1.3

### 1.1.0.0 Changes

* Adjusted buoyancy - the capsule no longer sinks after landing in water!
* Improved drag model - the capsule now rights itself more properly
* Improved the RemoteTech configs
* Added KIS configs
* Added RealChute configs

---

## Version 1.0.0.0 - initial release

* 2016-07-09
* Released for Kerbal Space Program 1.1.3

### New

---
