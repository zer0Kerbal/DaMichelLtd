---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.9.0
DaMichel Ltd (DML)
created: 28 Mar 2023
updated: 13 Apr 2022

TEMPLATE: ManualInstallation.md v1.1.9.0
created: 01 Feb 2022
updated: 27 Mar 2023

based upon work by Lisias -->

## [DaMichel Ltd (DML)][DML]

[Home](./index.md)


*Purveyors of fine Kichel Space Travel Supplies*

Agent, flags, and common files for DaMichel's parts addons.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the DaMichel folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/DaMichel/DaMichelLtd`
* Extract the package's `DaMichel` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/DaMichel` --> `<KSP_ROOT>/GameData/`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/DaMichel/DaMichelLtd`

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/DaMichel/DaMichelLtd`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/DaMichel/DaMichelLtd`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [DaMichel]
      + [DaMichelLtd]
        + [Agencies]
          ...
        + [Compatibility]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        * #.#.#.#.htm
        * changelog.md
        * DaMichelLtdLtd.version
        * License.txt
        * readme.htm
    * ModuleManager.ConfigCache
    ...
  * KSP.log
  ...
```

### Dependencies

* none

[DML]: https://forum.kerbalspaceprogram.com/index.php?/topic/208107-*/ "DaMichel Ltd (DML)"
