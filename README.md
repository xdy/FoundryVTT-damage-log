 # Damage Log

![GitHub Latest Release](https://img.shields.io/github/release/cs96and/FoundryVTT-damage-log?style=for-the-badge)
![Foundry Version](https://img.shields.io/badge/dynamic/json?label=Foundry%20Version&prefix=v&query=%24.compatibleCoreVersion&url=https%3A%2F%2Fraw.githubusercontent.com%2Fcs96and%2FFoundryVTT-damage-log%2Fmaster%2Fmodule.json&style=for-the-badge)
![Latest Release Downloads](https://img.shields.io/github/downloads/cs96and/FoundryVTT-damage-log/latest/total?style=for-the-badge)
![Forge Installs](https://img.shields.io/badge/dynamic/json?label=Forge%20Installs&query=package.installs&suffix=%25&url=https%3A%2F%2Fforge-vtt.com%2Fapi%2Fbazaar%2Fpackage%2Fdamage-log&colorB=4aa94a&style=for-the-badge)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/C0C057N35)

Damage Log is a FoundryVTT module that monitors for changes to characters' health, and displays those changes in a separate chatlog tab.  Changes can be easily be undone, or re-applied using the chat card's right-click menu.

![](images/damage-log.gif)

## Features
* Creates a separate "Damage Log" chatlog tab.  Whenever an actor takes damage or receives healing, a message containing the HP changes is added to the tab.
* The extra tab can be disabled, in which case the messages go to the normal chatlog.
* Damage can easily be reverted or re-applied using the message's right click menu.
* By default, only the GM can see the damage log.  The GM can optionally let players see the damage log for actors they are permissioned for (the minimum permission level is configurable, and defaults to "owner").
* The GM can also let players see limited damage info for all actors (i.e. the amount of damage taken, but not the old and new HP values).
* Works with [Ready Set Roll](https://foundryvtt.com/packages/ready-set-roll-5e/), [Midi QoL](https://foundryvtt.com/packages/midi-qol/), and probably works with other dice rolling modules too.
* Integrates with the [Tabbed Chatlog](https://github.com/cswendrowski/FoundryVTT-Tabbed-Chatlog) and [Customizable Chat Tabs](https://foundryvtt.com/packages/chat-tabs) modules (see below for more information).

### Tabbed Chatlog Integration
Damage Log is compatible with the [Tabbed Chatlog](https://github.com/cswendrowski/FoundryVTT-Tabbed-Chatlog) module, and will automatically add an extra tab on to the end of Tabbed Chatlog's tabs.

### Customizable Chat Tabs Integration
Damage Log is compatible with the [Customizable Chat Tabs](https://foundryvtt.com/packages/chat-tabs) module.  You will need to go into that module's settings, add a new tab, and select "Damage Log" messages to go into that tab.  Or alternatively add the Damage Log messages to one of your existing tabs.  Note that Damage Log messages have a type of "Other", so they will also appear in any other tabs that have "Other" messages selected.  To prevent this enable "Exclusive Mode" in Customizable Chat Tabs' settings.

## System Compatibility
Damage Log is currently compatible with the following systems.
* Achtung! Cthulhu 2d20 (`ac2d20`)
* Age of Sigmar: Soulbound (`age-of-sigmar-soulbound`)
* Dragonbane / Drakar & Demoner (`dragonbane`)
* Dungeons & Dragons v3.5 (`D35E`)
* Dungeons & Dragons 5th Edition (`dnd5e`)
* GURPS 4th Edition Game Aid (Unofficial) (`gurps`)
* Pathfinder 1st Edition (`pf1`)
* Pathfinder 2nd Edition (`pf2e`)
* Savage Worlds Adventure Edition (`swade`)
* Simple Worldbuilding (`worldbuilding`)
* Shadow Of The Demon Lord (`demonlord`)
* Star Wars 5e (`sw5e`)
* Story Shaper (`shaper`)
* Toolkit13 (13th Age Compatible) (`archmage`)
* Tormenta 20 (`tormenta20`)

## Installation
Damage Log can be installed using the Foundry module installer.  Alternatively, you can install it using the following manifest URL...<br>
https://github.com/cs96and/FoundryVTT-damage-log/releases/latest/download/module.json

## Support Me
If you find this module useful and would like to offer your support, why not buy me a coffee (or a beer)?

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/C0C057N35)
