# Flan's Mod Content Pack Overhaul
Overhaul of Flan's Mod's Modern Weapons, WW2, and Greylight Pack for Minecraft 1.7.10

## Overview
A while back I started putting together a custom modpack for Minecraft 1.7.10, but the official packs were underwhelming.
I set out to fix this over the past few years, but old websites and content packs gradually disappeared, and I wanted to save what I could while also overhauling functionality.
I've been sitting on this privately for a while, but now I thought I'd share it with the public.

Major changes include the addition of hundreds of new guns, new attachments, consumables, and a new ammo and battle damage system.
No armor, vehicles, or team functionality are present, but may be added soon at my own pace.
This overhaul is intended for maximum survival playability and goes well in survival worlds.

### Crafting

#### Getting Started: Weapons Boxes
Crafting guns is straightforward and similar to conventional Flan's mod. First you'll need a "Weapons Box" block (use NEI for the recipe). The general crafting recipe for gun weapons boxes is as follows:

[oak_log, oak_log, oak_log]

[fiberglass, dye, fiberglass]

[oak_log, oak_log, oak_log]

#### Weapons Boxes by Dye Color

| Dye                | Box Contents          |
|--------------------|-----------------------|
| **Ink Sac**        | Revolvers             |
| **Rose Red**       | Pistols               |
| **Cactus Green**   | Machine Pistols       |
| **Cocoa Beans**    | PDWs                  |
| **Lapis Lazuli**   | Shotguns              |
| **Purple Dye**     | Assault Rifles        |
| **Cyan Dye**       | Carbines              |
| **Light Gray Dye** | Battle Rifles         |
| **Grey Dye**       | Bolt-Action Rifles    |
| **Pink Dye**       | Snipers               |
| **Lime Dye**       | LMGs                  |
| **Dandelion Yellow**| Grenades             |
| **Light Blue Dye** | Grenade Launchers     |
| **Magenta Dye**    | Rocket Launchers      |
| **Orange Dye**     | Special               |

In addition to guns, melee weapons exist. 
Do not try to break blocks with these weapons; it won't work.
They do not come with durability, but are unenchantable.

Melee weapons are all crafted using the "Weapons Box - Melee" block:

[oak_log, oak_log, oak_log]

[fiberglass, diamond, fiberglass]

[oak_log, oak_log, oak_log]

#### Fiberglass
Fiberglass is a mod-exclusive crafting item made by combining glass blocks with redstone, yielding 16 items. The item itself is a holdover from old Flan's mod, but the recipe was changed.

#### Gunmetal
Gunmetal is a unique material required to make all guns and ammunition in the mod. 
Conventionally, gunmetal is made by smelting gold ingots. 
Installation of CraftTweaker scripts and extra mods (detailed below) widens the potential recipes and is recommended!!!

### New Guns
Between MW, WW2, and Greylight Pack overhauls, over a thousand guns have been added to the content pack. No gun was left behind, and minor variants, knockoffs, prototypes, paper weapons, and fictional designs from other games, franchises, and even of my own (and others'!) imagination have been included. Many of the models were taken from old content packs, so resolutions will differ somewhat. No paintjobs for guns were included; often, these guns only differ from each other visually by paintjob differences. 

A comprehensive list of all guns with their calibers and standard magazine size is given in the code files in an Excel file. Other information and potential future additions may also be found in this sheet; this is where I do all my planning and documentation for the mod.

### New Attachments
Many new atachments have been added. The attachment system is loosely based on the system in the Roblox game "Phantom Forces".
The attachment categories are as follows: Barrel, Optic, Grip, Stock, Generic.
Up to 4 generic attachment slots are available.
Such slots are useful for ammunition conversions as well as firemode attachments.

None of the attachments will visually modify your gun in a way that is visually interesting.
Instead, they will simply change the handling of your weapon and add reticles if applicable.
The reticles are also largely drawn from Phantom Forces.

#### Attachment Crafting

To craft attachments, you need to create attachment boxes.
Each attachment box represents a category of attachments.
The 5 attachment boxes available are as follows:

- Optic Attachments Box

[oak_log, oak_log, oak_log]

[fiberglass, glass, fiberglass]

[oak_log, oak_log, oak_log]

- Barrel Attachments Box

[oak_log, oak_log, oak_log]

[fiberglass, fiberglass, fiberglass]

[oak_log, oak_log, oak_log]

- Grip Attachments Box

[oak_log, oak_log, oak_log]

[fiberglass, stick, fiberglass]

[oak_log, oak_log, oak_log]

- Stock Attachment Box

[oak_log, oak_log, oak_log]

[fiberglass, oak_log, fiberglass]

[oak_log, oak_log, oak_log]

- Fire Selector Attachments Box

[oak_log, oak_log, oak_log]

[fiberglass, gold_ingot, fiberglass]

[oak_log, oak_log, oak_log]

### New Consumables
Many new consumables were added to enhance (or inhibit!) the player's in-game performance. These include foods, drinks, pills, and drugs of all kinds.

Consumables and other equipment are all crafted using the "Weapons Box - Support Equipment" block:

[oak_log, oak_log, oak_log]

[fiberglass, redstone_dust, fiberglass]

[oak_log, oak_log, oak_log]

### New Ammo
Instead of each gun having a unique magazine, like in old Flan's mod, I chose a system with standardized magazines. 
This reduces the amount of magazine items and makes ammunition more usable across different guns.

In addition to magazines, separate cartridges are sometimes used, especially for shotguns and older rifles. 
To get separate cartridges, it is highly recommended to first craft a Cartridge Box item from the Weapons Box, then craft that in your crafting grid to get a stack of cartridges.

If you have HBM's Nuclear Tech installed, certain cartridges with equivalent calibers are interchangeable, as long as you craft them into the other version first and run the Craft Tweaker script first.

#### Preferred Ammo
Certain guns are capable of taking different types of magazines: various shotgun shells, extended magazines, and so forth.
In this case, to preferentially use one ammunition type over another, press P, and in the top-left of your game should appear a GUI with preferred ammunition icons.
Select the ammunition type to preferentially load, and this one will be loaded before the others should you have multiple compatible ammunition types in your inventory.


### New Damage System
Most games, including old Flan's mod and most existing Flan's mod packs, are made with balance in mind. Balance is generally achieved by controlling damage with respect to firerate, magazine size, and other parameters.

This mod throws the entire concept of balance out the window, resulting in a Flan's mod experience that feels more like a tactical shooter. 

Before, it took multiple rifle-caliber hits to kill mobs and other players.
With the new damage setup, full diamond armor may not even protect you from the first shot.

The amount of damage dealt by a gun depends on two factors: the gun form factor and the caliber fired.
The caliber fired provides the base damage load, while the form factor serves as a multiplier.
If you have attachments on the gun, those will add as additional multipliers on top of the resultant damage of the form factor * caliber damage.

Here's an example of how this system works: say you have a gun loaded with ammunition that does 32 HP of damage/shot. Your gun is a sniper rifle, meaning the form factor multiplier is 2. Thus, your gun's damage would be 32 * 2 = 64 HP/shot.

Let's say you have another gun, an LMG, which uses the same caliber. Because it's an LMG, it's got a different form factor (1), therefore the gun does 32 * 1 = 32 HP/shot.

## Compatibility and Installation
This mod is for Minecraft 1.7.10. This content pack is not compatible with regular Flan's mod, or with any of the original Flan's mod content packs. 
Instead, use Flan's Mod Ultimate: https://www.curseforge.com/minecraft/mc-mods/flans-mod-ultimate-stability-edition

To install, create a folder called "Flan" in your ".minecraft" folder and place the content pack .jar file inside it. Then place Flan's Mod Ultimate in the "mods" folder. Conventional Flan's Mod installation.

All content packs must be used together, or you will have big problems!!!

### Crafting Alternatives
The use of HBM's Nuclear Tech Mod, Thermal Foundation, and Thermal Expansion is highly recommended. CraftTweaker scripts are included in the mod release to make eligible ammunition and materials interchangeable.
Script installation with CraftTweaker is elementary, just look it up or ask an AI.

HBM's Nuclear Tech Mod: https://github.com/HbmMods/Hbm-s-Nuclear-Tech-GIT/releases

Thermal Foundation: (https://www.curseforge.com/minecraft/mc-mods/thermal-foundation)

Thermal Expansion: (https://www.curseforge.com/minecraft/mc-mods/thermal-expansion)

Craft Tweaker: (https://www.curseforge.com/minecraft/mc-mods/crafttweaker)

HBM's Nuclear Tech and Thermal Expansion enable the use of alternative crafting recipes for materials.

#### Fiberglass
HBM's Nuclear Tech Mod has its own fiberglass item, which can be crafted into Flan's Mod fiberglass and vice versa in a 1:1 ratio.

#### Gunmetal
HBM's Nuclear Tech Mod has its own gunmetal ingots, which can be crafted into Flan's Mod gunmetal and vice versa in a 1:1 ratio.
Thermal mods come with tin, silver, and lead, whose ingots can be crafted in a 1:1:1 ratio into 6 gunmetal ingots.
The recipes are OreDicted, and should work with any other mods which contain these materials and are also properly OreDicted.

## FAQ
"Why didn't you make your own models?" - This was meant to be an overhaul of existing packs for playability in my survival worlds, not a grassroots pack of its own, or a gun model design project. 
If you want to make your own, go for it.

"Will you update the mod to future versions?" - No. 1.7.10 exclusive. 
I'm not going to do much more with this other than maybe a few more additions. 
My gaming days are largely behind me and I wanted to put this out there for others to enjoy, lest the flash drive I've been holding onto this in dies.

"If there are so many guns, what differentiates them?" - Not much. 
Most differences between guns come down to cosmetics. 
Handling differences play a role as well, but the difference is noticeable only to the most hardcore players.

## Credits
This gun content pack overhaul stands on the shoulders of giants who came before me. Content packs and mods whose contents were used include but are not limited to, with their original links (if available):

- Official Flan's Mod Content Packs (https://www.curseforge.com/minecraft/mc-mods/flans-mod-5-5-2)

- Greylight Content Pack (https://www.planetminecraft.com/mod/1-7-10-greylight-flans-content-pack/)

- Machetemen Arms Pack (https://www.planetminecraft.com/mod/machetemen-arms-pack-for-flans-mod-1710-134-3d-guns-and-melee/)

- HBM's Nuclear Tech Mod (https://github.com/HbmMods/Hbm-s-Nuclear-Tech-GIT/releases)

- Hearts of Iron Ore (https://www.curseforge.com/minecraft/modpacks/hearts-of-iron-ore)

- Tyrants and Plebeians (https://www.technicpack.net/modpack/tyrants-and-plebeians-windows.768490)

- Wild West Frontier (https://www.technicpack.net/modpack/wild-west-frontier.185231)

- And many others I don't remember...
