# Cryogenic Engines

A mod pack for Kerbal Space Program, focused on delivering a new set of engines for spacecraft.

* [Features](#features)
* [Dependencies](#dependencies)
* [Installation](#installation)
* [Optional Patches](#optional-patches)
* [External Compatibility](#features)
* [Contributing](#contributing)

## Features

This mod features several new engines that use a new resource, Liquid Hydrogen. This fuel provides awesome efficiency and fuel economy. Added engines are divided into two categories:

* **Sustainer Engines:** Four sustainer style engines in 1.25m, 1.875m, 2.5m and 3.75m size classes. Sustainers perform well at most altitudes but are less thrusty than LF/O engines, so may require boosters
* **Vacuum Engines:** Four vacuum-optimized engines in 1.25m, 1.875m, 2.5m and 3.75m size classes. These engines work best outside of at atmosphere and don't produce much thrust.

In addition, my CryoTanks mod is also bundled to provide fuel handling for Liquid Hydrogen.

* **Fuel Switching:** A set of patches provide fuel-switching features for most basic LF and LF/O tanks
* **Orbital Fuel Tanks:** A set of fuel tanks specially designed to contain LH2

For more information, check out the [CryoTanks readme](https://github.com/ChrisAdderley/CryoTanks/blob/master/README.md).

## Dependencies

### Required
These components are required for the mod to function and are bundled as part of any download:
* [ModuleManager (4.0.2)](https://github.com/sarbian/ModuleManager)
* [B9PartSwitch (2.8.0)](https://github.com/blowfishpro/B9PartSwitch)
* [Community Resource Pack (1.0.1)](https://github.com/BobPalmer/CommunityResourcePack)
* [CryoTanks (1.1.4)](https://github.com/ChrisAdderley/CryoTanks)
* [DynamicBatteryStorage (2.0.0)](https://github.com/ChrisAdderley/DynamicBatteryStorage)
* [DeployableEngines (1.0.1)](https://github.com/ChrisAdderley/DeployableEngines)

## Installation

To install, place the GameData folder inside your Kerbal Space Program folder. If asked to overwrite files, please do so.

NOTE: Do NOT rename or move folders within the GameData folder - this mod uses absolute paths to assets and will break if this happens.

## Optional Patches

Some extra patches are bundled that you can use to tweak your installation. To install them, drop the correct folder from the **Extras** folder into your KSP GameData Folder

* **CryoEnginesLFO**: Converts engines to use LF/O instead of LH2/O at the cost of some Isp
* **CryoEnginesNFAero**: Converts some appropriate engines to use LH2/O or LH instead of LF/O with some Isp and thrust tweaks
* **CryoEnginesRestock**: Converts some appropriate engines to use LH2/O instead of LF/O with some Isp and thrust tweaks

## External Mod Compatibility

This mod includes compatibility patches for the following mods:
* [KSP-AVC](https://github.com/CYBUTEK/KSPAddonVersionChecker): Provides version checking
* [Community Tech Tree](https://github.com/ChrisAdderley/CommunityTechTree): Provides an expanded, community-sourced technology tree for modders to use

## Contributing

I certainly accept pull requests. Please target all such things to the `dev` branch though!

## Translations

For translation instructions please see [Localization Instructions](https://github.com/ChrisAdderley/CryoEngines/blob/master/GameData/CryoEngines/Localization/Localization.md)

* **Spanish:** KSP forum user fitiales
* **Chinese:** KSP forum user Next_Star_Industries
* **Russian:** KSP forum user Next_Star_Industries and vladmir_v
* **French:** KSP forum user Next_Star_Industries
* **German:** KSP forum user Three_Pounds

## Licensing

The art assets in this pack (all .dds, .png and .mu files) are distributed under an All Rights Reserved license. You may not redistribute or re-use these assets without express permission from the author.

Any bundled mods are distributed under their own licenses:
* ModuleManager by ialdabaoth and sarbian is distributed under a Creative Commons Sharealike license. More details, including source code, can be found [here](http://forum.kerbalspaceprogram.com/threads/31342-0-20-ModuleManager-1-3-for-all-your-stock-modding-needs?p=528607&viewfull=1#post528607)
* The Community Resource Pack by RoverDude is also distributed under its own license. Please find source and more details [here](https://github.com/BobPalmer/CommunityResourcePack)
* B9PartSwitch by blowfish is also distributed under its own license. Please find source and more details [here](https://github.com/blowfishpro/B9PartSwitch)

Everything else is distributed under the MIT license.

Copyright (c) 2019 Chris Adderley
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
