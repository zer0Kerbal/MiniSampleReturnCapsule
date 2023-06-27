# Changelog  
  
| modName    | Mini Sample Return Capsule (MSRC)                                    |
| ---------- | -------------------------------------------------------------------- |
| author     | CobaltWolf, AlbertKermin and zer0Kerbal                              |
| license    | SimpleBSD-2                                                          |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/204186-*/)    |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/MiniSampleReturnCapsule)   |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/MiniSampleReturnCapsule) |
| spacedock  | (https://spacedock.info/mod/831)                                     |
| ckan       | MiniSampleReturnCapsule                                              |

## Version 1.4.4.0-release - `<Спасибо evanisrael>` edition

* Released
  * 27 Jun 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

### Change Summary 1.4.4.0

* Localize
  * ![Russian (Русский)](https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/RU.png) Russian (Русский)
  * Спасибо [evanisrael](https://github/evanisrael)

### Changes 1.4.4.0

#### Parts 1.4.4.0

* Update
  * category = Science
  * [msrc-cargobay.cfg] v1.4.4.0
  * [msrc-parachute.cfg] v1.4.4.0
    * adjust antenna specifications to match Commtech 16S

#### Compatibility 1.4.4.0

* Update
  * [GPO]
  * Kerbalism.cfg v1.0.3.0

#### Localization 1.4.4.0

* Add
  * Russian (Русский)
    * [ru.cfg] v1.0.0.0
    * Спасибо [evanisrael](https://github/evanisrael)
  * Translation guides
    * [readme-ru.md] v1.0.1.0
    * [quickstart-ru.md] v1.0.0.0
    * Спасибо [evanisrael](https://github/evanisrael)
* Update
  * header, give credit
  * fuel switcher strings
  * [ru.cfg] v1.0.1.0
  * [en.cfg] v1.1.1.0
  * [pr-br.cfg] v1.1.1.0

#### Documentation 1.4.4.0

* Update
  * [readme.md] v1.4.4.0
    * fixed KSP shield pulling data from Taerobee
  * [ReleaseLayout.md] 1.4.4.0
  * [Attributions.md] v1.4.4.0
  * [Localizations.md] v1.4.4.0
  * [PartsCatalog.md] v1.4.3.1
    * minor linting
  * [404.md] v1.4.4.0
    * update from template


---


## Version 1.4.3.0-release - `<Scanning Rodger, Rodger>` edition

* Released
  * 07 May 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

## Change Summary

* Kerbalism patch riding coattails - thank you [Rodg88](https://github.com/Rodg88)
* Found the Science Container in the Reentry Segment (parachute), Val was using it to store her lunch.
* New manufacturing tech resulting from peanut butter spillage from Val's lunch has toughened up both segments
* BIOS/OS update now allows for SCANsat compatibility
* now can search for `msrc` in editors to find parts
* updating documentation
* new Hero logo/cover
* linting, updating and general tom foolery

* Issues
  * closes #91 - Mini Sample Return Capsule (MSRC) 1.4.3.0-release `<Scanning Rodger, Rodger>` edition
  * closes #92 - 1.4.3.0 Additional Tasks
  * closes #19 - SCANsat compatibility
  * closes #88 - [Request] Allow Science Retrieval
  * closes #89 - [Bug] Parachute/Core Model Linked to Antenna Durability Snapping.
  * closes #90 - [BUG] Kerbalism config

---

## Version 1.4.2.2-release - `<Zippity Don't Cha>`

* 15 Apr 2022  
* Release for Kerbal Space Program [KSP 1.12.x]

### Removed 1.4.2.2

* [Kerbalism.zip]
  * Thank you [N3N]
    * <KSP_ROOT>GameData\MiniSampleReturnCapsule\Compatibility\Kerbalism.zip
    * I accidentally left it there when I sent an updated file; and it corrupted the release. Again, apologies for that.
    * concerned that calling KerbalismDefault will tell MM that it is installed.
  * fixes #81 - [Bug 🐞]: Kerbalism.zip

### Update 1.4.2.2

* docs/
* automation
* documentation
* Add
  * [Notices.md]
  * [Attributions.md]
  * [ManualInstallation.md]

### Status 1.4.2.2

* Issues
  * closes #82 - Mini Sample Return Capsule 1.4.2.2-release `<Zippity Don't Cha>`
  * closes #83 - 1.4.2.2 Verify Legal Mumbo Jumbo
  * closes #84 - 1.4.2.2 Update Documentation
  * closes #85 - 1.4.2.2 Update Social Media
* Pull Request  
* #80 - [ImgBot] Optimize images - contributed by imgbot[bot]

---  

## Version 1.4.2.1-release - `<Before, For, After>`

* 30 Mar 2022  
* Release for Kerbal Space Program [KSP 1.12.x]

### Fixed 1.4.2.1

* [Kerbalism.cfg] v1.0.1.0
  * Thank you [AmanitaVerna]
  * 'more than one pass specifier detected'
  * removed :FOR[MiniSampleReturnCapsule] and kept :BEFORE/AFTER[KerbalismDefault]
  * concerned that calling KerbalismDefault will tell MM that it is installed.
  * fixes #71 - [Bug 🐞]: Warnings from Module Manager for kerbalism.cfg

### Update 1.4.2.1

* docs/
* automation
* documentation
* [MiniSampleReturnCapsule.version]
  * removed
    * [KSP_VERSION_MAX]

### Status 1.4.2.1

* Issues
  * closes #73 Mini Sample Return Capsule 1.4.2.1-release `<Before, For, After>`
  * closes #74 1.4.2.1 Verify Legal Mumbo Jumbo
  * closes #75 1.4.2.1 Update Documentation
  * closes #76 1.4.2.1 Update Social Media
  * closes #71 [Bug 🐞]: Warnings from Module Manager for kerbalism.cfg

* #70 - 1.4.2.0 release - contributed by zer0Kerbal
* #72 - upstream - contributed by zer0Kerbal
* #77 - Version 1.4.2.1 - `&lt;Before, For, After&gt;` - contributed by zer0Kerbal
* #71 - [Bug &#55357;&#56350;]: Warnings from Module Manager for kerbalism.cfg
* #73 - Mini Sample Return Capsule 1.4.2.1-release `&lt;Before, For, After&gt;`
* #74 - 1.4.2.1 Verify Legal Mumbo Jumbo
* #75 - 1.4.2.1 Update Documentation
* #76 - 1.4.2.1 Update Social Media

---

## Version 1.4.2.0-release

* 01 Feb 2022
* KSP 1.12.3

### Localization 1.4.2.0

* added <pt-br.cfg>
* Brazil Portuguese (Português Brasil) - Thank you [soldanithiago](https://github.com/soldanithiago)
* added localization quickstart.md
* closes #34 - Localization - Brazil Portuguese (Portugu├¬s Brasil) <pt-br.cfg> 

### Added 1.4.2.0

* Kerbalism compatibility
  * [Kerbalism.cfg] v1.0.0.0
  * Thank you [Breach Candy#6218]
  * closes #47 - Kerbalism config
  
### Compatibility 1.4.2.0

* Add
  * [TweakScale.cfg] v1.0.1.9
  * [KerbNet.cfg] v1.0.1.9
  * [GPOSppedFuelPump.cfg] v1.0.1.9
  * [CommunityCategoryKit.cfg] v1.0.1.9
* Update
  * [RemoteTech.cfg] v1.0.1.9
  * [kOS.cfg] v1.0.1.9
* Related Issues:
  * closes #65 - TweakScale.cfg
  * closes #64 - KerbNet.cfg
  * closes #63 - GPOSppedFuelPump.cfg
  * closes #62 - CommunityCategoryKit.cfg
  * closes #61 - Add Compatibility
  
### Convert Change Log 1.4.2.0

* From Kerbal ChangeLog to markdown
* Convert [Changelog.cfg] --> [changelog.md]
* Create changelog.md
* Delete Changelog.cfg
* closes #57 - 1.4.2.0 Update changelog
  
### Wiki 1.4.2.0

* Added localization.md

### Part Volume Math

| ***part        |   style    | diameter (m) | height (m) | width (m |   math   | radius (m) |      m³ | Liters*** |
| :------------- | :--------: | -----------: | ---------: | -------: | :------: | ---------: | ------: | --------: |
| msrc-parachute | hemisphere |        0.625 |       0.37 |          | (2/3)πr³ |     0.3125 | 0.06392 |     63.92 |
| msrc-cargobay  |  cylinder  |        0.625 |       0.31 |          |   πr²h   |     0.3125 | 0.09511 |     95.11 |

* [mrsc-cargobay]
  * [ModuleCargoPart] was 125 now 100
    * type = cylinder
    * radius = 0.3125m
    * height = 0.32m
    * volume =  0.09511 m³
    * m³ x 1000L = 95.11 m³
    * packedVolume = 100
  * Update
    * Add zer0Kerbal to [author]
    * [maximum_drag] changed from 0.2 to 0.1
    * [angularDrag] changed from 2 to 1.5
    * [maxTemp] changed from 2900 to 2500
    * [thermalMassModifier] changed from 5.0 to 1.0 
    * [ModuleCargoBay]
      * [lookupRadius] changed from 0.9 to 0.4
* [mrsc-parachute]
  * [ModuleCargoPart] was 100 now 75
    * type = hemisphere
    * radius = 0.3125m
    * height = 0.37m
    * volume =  0.06392 m³
    * m³ x 1000L = 63.92 m³
    * packedVolume = 75
  * Update
    * Add zer0Kerbal to [author]
    * [maximum_drag] changed from 0.2 to 0.3
    * [minimum_drag] = 0.3 to 0.1
    * [angularDrag] changed from 2 to 1.5
    * [ModuleCommand]
      * Add [hasHibernation] = True
      * Add [hibernation] = False
      * Add [hibernateOnWarp] = True
      * Add [hibernationMultiplier] = 0.00125
    * [ModuleReactionWheel
      * Add [hasHibernation] = True
      * Add [hibernation] = False
      * Add [hibernationMultiplier] = 0.00125
    * [ModuleSAS]
      * [SASServiceLevel] changed from 1 to 2

### Maintenance 1.4.2.0

* Incremental Upgrades
  * minor housekeeping
  * linting and duct taping
  * patch dusting (mostly removing construction dust (comments)
  * modernization, polish, update pass on part.cfg's
  * automated back end processes.
  * consolidated footer in files

### Status 1.4.2.0

* Issues
  * closes #45 - Localization - English (United States)] <en-us.cfg>
  * closes #47 - Kerbalism config
  * closes #48 - Update Mini Science Return Capsule (end beta) (MSRC) 1.4.2.0
  * closes #51 - Release 1.4.2.0-release <To kerbal or to not kerbal...>  
  * closes #52 - Version 1.4.2.0-release
  * closes #53 - 1.4.2.0 Verify Legal MumboJumbo
  * closes #54 - 1.4.2.0 Update documentation
  * closes #55 - 1.4.2.0 - Social Media
  * closes #56 - 1.4.2.0 Update release notes
  * closes #57 - 1.4.2.0 Update changelog
  * closes #58 - 1.4.2.0 Update readme
  * closes #8 - Localization
  * closes #25 - # Version 1.4.1.0
  * closes #28 - Localization - en-us.cfg (English)
  * closes #27 - Localization - pt-br.cfg Brazil
  * closes #26 - Localization - zh-cn.cfg - Simplified Chinese
* Updates
  * updates #46 - Localization - Master

* #18 - 1.4.1.0 - contributed by zer0Kerbal
* #59 - 1.4.2.0 Update [readme.md] v1.5.4.0 - contributed by zer0Kerbal
* #60 - Create Kerbalism.cfg - contributed by zer0Kerbal
* #66 - Compatibility Patches :cool: - contributed by zer0Kerbal
* #67 - 1.4.2.0 release - contributed by zer0Kerbal
* #68 - Translation to Portuguese-BR - contributed by zer0Kerbal
* #7 - Localization.md
* #8 - Localization
* #10 - [ModuleCargoPart] packedVolume seems a tad high
* #15 - duplicate 
* #16 - Tarsier Space Tech compatibility
* #17 - add kOS compatibility
* #20 - RemoteTech.cfg
* #25 - # Version 1.4.1.0
* #26 - Localization - zh-cn.cfg - Simplified Chinese
* #27 - Localization - pt-br.cfg Brazil
* #28 - Localization - en-us.cfg (English)
* #29 - Localization
* #34 - Localization - Brazil Portuguese (Portugu&#234;s Brasil) &lt;pt-br.cfg&gt;  
* #45 - Localization - English (United States)] &lt;en-us.cfg&gt; 
* #47 - Kerbalism config
* #48 - Update Mini Science Return Capsule (end beta) (MSRC) 1.4.2.0
* #51 - Release 1.4.2.0-release &lt;To kerbal or to not kerbal...&gt;
* #52 - Version 1.4.2.0-release
* #53 - 1.4.2.0 Verify Legal MumboJumbo
* #54 - 1.4.2.0 Update documentation
* #55 - 1.4.2.0 - Social Media
* #56 - 1.4.2.0 Update release notes
* #57 - 1.4.2.0 Update changelog
* #58 - 1.4.2.0 Update readme
* #61 - Add Compatibility
* #62 - CommunityCategoryKit.cfg
* #63 - GPOSppedFuelPump.cfg
* #64 - KerbNet.cfg
* #65 - TweakScale.cfg

---

## Version 1.4.1.0 - `<Packed and ready to return>`

* 2021-09-16
* Released for Kerbal Space Program 1.12.2

* DO A CLEAN INSTALL: DELETE EXISTING THEN RE-INSTALL</color></b>

### Update 1.4.1.0

### Localization 1.4.1.0

* [Localization\readme.md]
  * to version 2.0.0.0 which closes #7

* created .legal folder with forum adoption approval

### Added 1.4.1.0

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

### Updated 1.4.1.0

* [mrsc-cargobay] and [msrc-parachute]
  * [ModuleCargoPart] packedVolume = 125 from 1100 (based upon volume of a column~ish)
  * [ModuleCargoPart] packedVolume = 100 from 1200 (based upon volume of a hemisphere~ish)

### Maintenance 1.4.1.0 

* Incremental Upgrades
  * minor housekeeping
  * linting and duct taping
  * patch dusting (mostly removing construction dust (comments)
  * modernization, polish, update pass on part.cfg's
  * automated back end processes.

### Status 1.4.1.0 

* Issues
  * closes #7 Localization/readme.md
  * closes #10 [ModuleCargoPart] packedVolume seems a tad high
  * closes #14 - back end
  * closes #16 Tarsier Space Tech compatibility
  * closes #17 add kOS compatibility
  * closes #20 add RemoteTech description blurb
  * updated #8 us-en.cfg should be complete

### Possible future changes 1.4.1.0

* ***❓ ❔ seems high : ❓ ❔***
  * [breakingForce = 50]
  * [breakingTorque = 50] seems high ???
  * [crashTolerance = 12]

* update Localization\readme.md --> 2.0.0.0 which closes #11

---

## Version 1.4.0.0-adoption - `<Old dog, new tricks>`

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
