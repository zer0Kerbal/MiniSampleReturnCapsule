# Release for KSP 1.12.2
# Added
- Localization
  - us-en.cfg should be completed
  - added localization readme.md
  - updated part tags

# Updated
- Cargo Pass
  - added ModuleCargoPart

# Updated
- modernization, polish, update pass on part.cfg's
  - fully updated and modernized all parts
  - added @thumbs

# Changes  
- [mrsc-cargobay]
  - moved from [Utility] to [Payload]
  - updated [bulkheadProfiles] from size0 to size0
  - added [ModuleCargoPart] packedVolume = 1100 (based upon volume of a column~ish)
  - added [CoPOffset] = 0.0, 0.2, 0.0
  - added [CoLOffset] = 0.0, -0.05, 0.0
  - added [thermalMassModifier] and set it to 5.0 to match stock 1.25m service bay
  - didn't adjust [xxxDrag] because settings match stock 1.25m service bay
  - adjusted [lookupRadius] from 0.9 to 0.4 as suggested by @draqsko
  - added [lookupCenter] = 0.0, 0.1306, 0.0 as suggested by @draqsko
  - added [partTypeName] = Service bay to match stock 1.25m service bay
- [mrsc-parachute] 
  - moved [category] to [Pods] from [Utility] 
  - added [RSCFX]  
  - added [ModuleScienceContainer]  
  - added [ModuleDataTransmitter] 
  - [ModuleRCS] --> [ModuleRCSFX]
  - added [SASServiceLevel = 1] allows to hold (prograde/retrograde)
  - added [torqueResponseSpeed = 10] to [ModuleReactionWheel]
  - added [hasHibernation, hibernation, hibernateOnWarp, hibernationMultiplier] to [ModuleCommand]
  - adjusted EC consumption form 0.020 -> 0.005 for [ModuleCommand]
  - added [CrewCapacity = 0]
  - adjusted [maxTemp] to 1200 from 2000 to match mk1pod
  - added [skinMaxTemp] = 2200 to match mk1pod
  - added [skinInternalConductionMult] = 0.625 to match mk1pod
  - added [ModuleConductionMultiplier] to match mk1pod
  - added [heatConductivity] = 0.1  to match mk1pod
  - adjusted [maximum_drag] to 0.2 from 0.01
  - adjusted [minimum_drag] to 0.15 from 0.01
  - adjusted [angularDrag] to 1.5 from 0.1
  - added [ModuleCargoPart] packedVolume = 1200 (based upon volume of a sphere~ish)
  - adjusted [ModuleDragModifier][DEPLOYED][dragModifier] to 6 from 24
  - adjusted [ModuleDragModifier][DEPLOYED][dragModifier] to 9 from 6 - landed at just under 10m/s
  - added [explosionPotential] = 0
  - added [buoyancy = 6.0] darn thing refused to float!
  
  - *** Possible future changes ***
    - [breakingForce = 50] and [breakingTorque = 50] seems high ???
   
#  >>-- Adoption for curation by zer0Kerbal --<<
- Restructure folders
- moved models/textures into /Assets/
- updated .mu pointers from .tga -> .dds
- initial Localization push
- created GitHub Repo
- created Curseforge page
- updated SpaceDock
- renamed GitHub repository to MiniSampleReturnCapsule
- updated CKAN/NetKAN
- created new forum thread
- updated to automated back end processes.
- automated deploy/release process
- moved changelog into separate file
- Changelog.md -> Kerbal Changelog Changelog.cfg
- created Readme.md
- added .version file
- added license file(s)
- merged in patches
- linting and duct taping