# Overview

Do you like terraform stations from my mod [Aesthetic Terraform Stations](https://steamcommunity.com/sharedfiles/filedetails/?id=2622411084)?  Do you also want to have properly-skinned terraform stations using the crisis ships (Contingency, Unbidden _et al_, Prethoryn)?  Then this mod is for you!

# Changes

Adds terraform station definitions with an active terraforming beam for for all of the built-in crisis graphical cultures (`ai_01`, `ai_02`, `extra_dimensional_01`, `extra_dimensional_02`, `extra_dimensional_03`, `swarm_01`), required for Aesthetic Terraform Stations to apply the correct appearance.  Also supports other mods which add shipsets using the crisis models (see below for a list of those currently supported).

## Compatibility

Should work with practically everything that also works with Aesthetic Terraform Stations and one or more of the supported shipset mods.

Built for Stellaris version 3.7 "Canis Minor."  Not compatible with achievements, but neither is the dependency.

### Required Dependency Mods

* [Aesthetic Terraform Stations](https://steamcommunity.com/sharedfiles/filedetails/?id=2622411084) enables the very old-school terraform stations as visual markers for terraforming planets

### Supported Shipset Mods

These mods are explicitly supported.  Using a different crisis shipset mod?  Leave a comment and I can probably add support for it to this mod.

* [Animated Holosphere Portraits: Revisited](https://steamcommunity.com/sharedfiles/filedetails/?id=2592592503) adds a shipset built using the Unbidden models
* [Animated Silicoid Portraits: Revisited](https://steamcommunity.com/sharedfiles/filedetails/?id=2579736379) adds a shipset built using the Contingency models
* [Expanded Gestalts: Forgotten Queens](https://steamcommunity.com/sharedfiles/filedetails/?id=1715190550) adds a shipset built using the Prethoryn models
* [Swarm Ship Set (standalone)](https://steamcommunity.com/sharedfiles/filedetails/?id=2532923000) adds a shipset built using the Prethoryn models
* [Unbidden Ship Set (standalone)](https://steamcommunity.com/sharedfiles/filedetails/?id=2545935786) adds a shipset built using the Unbidden models

## Changelog

* 1.0.0 Initial version

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/crisis_shipsets_terraform_station_aesthetic)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.