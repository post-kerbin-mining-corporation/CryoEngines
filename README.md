# CryoEngines

A mod pack for Kerbal Space Program, focused on delivering a new set of engines for spacecraft.

* [Features](#features)
* [Dependencies](#dependencies)
* [Installation](#installation)
* [Optional Patches](#optional-patches)
* [External Compatibility](#features)
* [Contributing](#contributing)

## Features

This mod features several new engines that use a new resource, Liquid Hydrogen. This fuel provides awesome efficiency and fuel economy. Added engines are divided into two categories

* **Sustainer Engines:** Three sustainer style engines in 1.25m, 2.5m and 3.75m size classes. Sustainers perform well at most altitudes but are less thrusty than LF/O engines
* **Vacuum Engines:** Three vacuum-optimized engines in 1.25m, 2.5m and 3.75m size classes. These engines work best in orbit. 

In addition, my CryoTanks mod is also bundled to provide fuel handling for Liquid Hydrogen.

* **Fuel Switching:** A set of patches provide fuel-switching features for most basic LF and LF/O tanks
* **Orbital Fuel Tanks:** A set of fuel tanks specially designed to contain LH2

For more information, check out the [CryoTanks readme](https://github.com/ChrisAdderley/CryoTanks/blob/master/README.md).

## Dependencies

### Required
These components are required for the mod to function and are bundled as part of any download:
* [ModuleManager (3.1.0)](https://github.com/sarbian/ModuleManager)
* [B9PartSwitch (2.4.5)](https://github.com/blowfishpro/B9PartSwitch)
* [Community Resource Pack (1.0.0)](https://github.com/BobPalmer/CommunityResourcePack)
* [CryoTanks (1.0.3)](https://github.com/ChrisAdderley/CryoTanks)
* [DynamicBatteryStorage (1.6.0)](https://github.com/Angel-125/KerbalActuators)
* [DeployableEngines (0.1.0)](https://github.com/ChrisAdderley/DeployableEngines)

## Installation

To install, place the GameData folder inside your Kerbal Space Program folder. If asked to overwrite files, please do so.

NOTE: Do NOT rename or move folders within the GameData folder - this mod uses absolute paths to assets and will break if this happens.

## Optional Patches

Some extra patches are bundled that you can use to tweak your installation. To install them, drop the correct folder from the **Extras** folder into your KSP GameData Folder

* **CryoEnginesLFO**: Converts engines to use LF/O instead of LH2/O at the cost of some Isp

## External Mod Compatibility

This mod includes compatibility patches for the following mods:
* [KSP-AVC](https://github.com/CYBUTEK/KSPAddonVersionChecker): Provides version checking 
* [Community Tech Tree](https://github.com/ChrisAdderley/CommunityTechTree): Provides an expanded, community-sourced technology tree for modders to use

## Contributing

I certainly accept pull requests. Please target all such things to the `dev` branch though!

## Licensing

The configuration and code in this pack are distributed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (http://creativecommons.org/licenses/by-nc-sa/4.0/legalcode). You are free to share and adapt the materials only for non-commercial purposes and when providing appropriate attribution. Any derivatives must be distributed under the same license.

The art assets in this pack (all models and textures) are distributed under an All Rights Reserved License. You may not redistribute or re-use these assets without express permission from me.

Any bundled dependencies in the release packages are distributed under their own licenses
