# Flan's Mod Content Pack Overhaul
Overhaul of Flan's Mod's Modern Weapons Pack for Minecraft 1.7.10

Update 6/4/2026 - Nothing has been released yet, I will assemble the files and release this shortly. Check back in a few days.

## Overview
A while back I started putting together a custom modpack for Minecraft 1.7.10, but the official packs were underwhelming.
I set out to fix this over the past few years, but old websites and content packs gradually disappeared, and I wanted to save what I could while also overhauling functionality.
I've been sitting on this privately for a while, but now I figured I'd share it with everybody.

Major changes include the addition of hundreds of new guns (with models compiled from various packs), new attachments, consumables, and a new ammo and battle damage system.
No armor, vehicles, or team functionality are present, but may be added soon at my own pace.
This overhaul is intended for maximum survival playability.

### Crafting
#### Getting Started: Weapons Boxes
Crafting guns is straightforward and similar to conventional Flan's mod. First you'll need a "Weapons Box" block (use NEI for the recipe). The general crafting recipe for gun weapons boxes is as follows:

[oak_log, oak_log, oak_log]

[fiberglass, dye, fiberglass]

[oak_log, oak_log, oak_log]

#### Fiberglass
Fiberglass is a mod-exclusive crafting item made by combining glass with redstone, yielding multiple items. The item itself is a holdover from old Flan's mod, but the recipe was changed.

#### Gunmetal
Gunmetal is a unique material required to make all guns and ammunition in the mod.

### New Guns
Between this and the WW2 Pack overhaul, over a thousand guns have been added to the content pack. No gun was left behind, and minor variants, knockoffs, prototypes, paper weapons, and fictional designs from other games, franchises, and even of my own imagination have been included. Many of the models were taken from old content packs, so resolutions will differ somewhat. No paintjobs for guns were included; often, these guns only differ from each other visually by paintjob differences. A comprehensive list of all guns with their calibers and standard magazine size is given in the code files in an Excel file. In the future, I might go back and make individual models for each gun.

### New Attachments
Many new atachments have been added. The attachment system is loosely based on the system in the Roblox game "Phantom Forces".
The attachment categories are as follows: Barrel, Optic, Grip, Stock, Generic.
Up to 4 generic attachment slots are available.
Such slots are useful for ammunition conversions as well as firemode attachments.

None of the attachments will visually modify your gun in a way that is visually interesting.
Instead, they will simply change the handling of your weapon and add reticles if applicable.
The reticles are also largely drawn from Phantom Forces.

### New Consumables
Many new consumables were added to enhance (or inhibit!) the player's in-game performance. These include foods, drinks, pills, and drugs of all kinds.
[to be continued]

### New Ammo
Instead of each gun having a unique magazine, like in old Flan's mod, I chose a system with standardized magazines. This reduces the amount of magazine items and makes ammunition more usable across different guns, allowing for more flexibility
[to be continued]

### New Damage System
Most games, including old Flan's mod and most existing Flan's mod packs, are made with balance in mind. Balance is generally achieved by controlling damage with respect to firerate, magazine size, and other parameters.
But I threw the entire concept of balance out the window. 
The result is a Flan's mod that feels more like a tactical shooter. 
Before, it took multiple rifle-caliber hits to kill mobs and other players.
With my new damage setup, you'll be lucky to survive a hit from sniper rifle in full diamond armor.

The amount of damage dealt by a gun depends on two factors: the gun form factor and the caliber fired.
The caliber fired provides the base damage load, while the form factor serves as a multiplier.
If you have attachments on the gun, those will add as additional multipliers on top of the resultant damage of the form factor * caliber damage.

Here's an example of how this system works: say you have a gun loaded with ammunition that does 32 HP of damage/shot. Your gun is a sniper rifle, meaning the form factor multiplier is 2. Thus, your gun's damage would be 32 * 2 = 64 HP/shot.

Let's say you have another gun, an LMG, which uses the same caliber. Because it's an LMG, it's got a different form factor (1), therefore the gun does 32 * 1 = 32 HP/shot.

You might ask, what differentiates different guns then?
I'll answer honestly: it's largely cosmetics and personal preference.
So why so many guns? *shrug* I don't really know, but it's fun.
It's not the best game design, but it's fun for me, and if you don't like it, don't play it.

### Compatibility and Installation
This mod is for Minecraft 1.7.10. This content pack is not compatible with regular Flan's mod, or with any of the original Flan's mod content packs. 
Instead, use Flan's Mod Ultimate: https://www.curseforge.com/minecraft/mc-mods/flans-mod-ultimate-stability-edition

To install, create a folder called "Flan" in your ".minecraft" folder and place the content pack .jar file inside it. Then place Flan's Mod Ultimate in the "mods" folder. Conventional Flan's Mod installation.

#### Crafting Alternatives
The use of HBM's Nuclear Tech Mod, Thermal Dynamics, and Thermal Expansion is highly recommended. CraftTweaker scripts are included in the mod release to make eligible ammunition and materials interchangeable.
Script installation with CraftTweaker is elementary, just look it up or ask an AI.

HBM's Nuclear Tech Mod: (link)

Thermal Dynamics: (link)

Thermal Expansion: (link)

Craft Tweaker: (link)

HBM's Nuclear Tech and Thermal Expansion enable the use of alternative crafting recipes for materials.

##### Fiberglass
HBM's Nuclear Tech Mod has its own fiberglass item, which can be crafted into Flan's Mod fiberglass and vice versa in a 1:1 ratio.

##### Gunmetal
HBM's Nuclear Tech Mod has its own gunmetal ingots, which can be crafted into Flan's Mod gunmetal and vice versa in a 1:1 ratio.

Thermal mods come with tin, silver, and lead, whose ingots can be crafted in a 1:1:1 ratio into 6 gunmetal ingots.

The recipes are OreDicted, and should work with any other mods which contain these materials and are also properly OreDicted.


### FAQ
"Why didn't you make your own models?" - This was meant to be an overhaul of existing packs for playability in my survival worlds, not a grassroots pack of its own, or a gun model design project. 
If you want to contribute to it, go for it.

"Will you update the mod?" - No. 1.7.10 exclusive. 
I'm not going to do much more with this other than maybe a few more additions. 
My gaming days are behind me and I wanted to put this out there, lest the flash drive I've been holding onto this in dies in case anybody else wants to enjoy it.

### Credits
This gun content pack overhaul stands on the shoulders of giants who came before me. Content packs and mods whose contents were used include but are not limited to, with their original links (if available):

- Official Flan's Mod Content Packs (https://www.curseforge.com/minecraft/mc-mods/flans-mod-5-5-2)

- Greylight Content Pack (link)

- Machetemen Arms Pack (link)

- HBM's Nuclear Tech Mod (link)

- Hearts of Iron Ore (link)

- Tyrants and Plebeians (link)

- Wild West Frontier (link)

- And others which I don't remember...
