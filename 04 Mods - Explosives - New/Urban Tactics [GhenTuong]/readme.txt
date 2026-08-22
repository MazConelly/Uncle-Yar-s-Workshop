-Module:
Urban Tactics [GhenTuong]
https://www.moddb.com/mods/stalker-anomaly/addons/gt-urban-tactics/

----------------------------------------------------------
-Compatibility:
NOTE: You still need the original mod. Disable the configs and textures/ui folders.

----------------------------------------------------------
-Explanation:

The NPC loadout configs will work for the NPC loadout rework in this pack (00 Vanilla - Weapons\NPC loadouts files rank fix), and won't wipe clean the sections it tries to add items to.
Traders will now sell the items at mid goodwill, instead of out of the gate (this is to not completely devalue the vanilla smoke nades).
The M662 and M18 will be sold by NATO leaning factions, and the explosive charge by solvent factions. Otherwise connected traders might still sell both.
Crafting file now will only add instead of override the crafting sections its trying to add the recipes to, leading to only the tripwires being available.
Icons gathered into a single file.


An option is offered for Ncenka's Expanded.
https://www.moddb.com/mods/stalker-anomaly/addons/gt-ut-expanded-by-ncenka
In addition to the above:
Icons gathered into a single file. The icon for the explosive charge was too big for 1x1 dimensions, so I moved it a bit and made it 1x2. The icon for the RPG-7 tripwire also looked weird (is that a mace after Ivy Valentine was done with it?), so I remade it a little bigger.


Integration into:
AlifePlus. This support is experimental.
	With AP, veterans are expected to trade grenades, buying one and selling excedents of 3, but rookies won't trade them in either way.
Lootboxes

----------------------------------------------------------
-Patches:

The following patches will cover relevant mod weapons to load the flares in their grenade launchers.

Boomsticks and Sharpsticks
BaS Lite includes its own patch.

Misc. Weapon Pack

Other loose mods. This includes:
	AR Pack
	Alex's AK107
	ATHI's Sig Spear
	Billwa's Milkor M32
	Lewdnatic's FAD, Groza Duty


STALKER 2 HoC Grenade Animation
Its animations will be used.
NOTE: You still need the original mod.

EFT Grenade Collision Sounds

----------------------------------------------------------
-Known issues:

GT's original mod has three scripts: one for the flares when they explode, another for the smokes, and another for the tripwire.
Ncenka's Expanded repeats the code of the tripwire script again and again for each tripwire, even when they're not explosives. I haven't tested if they actually flare or smoke up instead of exploding, but all the same, that feels horribly ineficient.
This would need reworking the bind_mine.script code to work for all tripwires at once, and make sure to include the coding to differentiate between explosive, smoke, and flare, and act for each as such.