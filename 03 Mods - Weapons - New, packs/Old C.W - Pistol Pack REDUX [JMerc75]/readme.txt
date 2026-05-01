-Module:
Old C.W - Pistol Pack REDUX [Jmerc]
https://www.moddb.com/mods/stalker-anomaly/addons/old-cw-pistol-pack-redux

----------------------------------------------------------
-Compatibility:

NOTE: You still need the original mod. Disable the original configs folder

Important: This patch requires a new game if you were already using this mod.

----------------------------------------------------------
-Explanation:

Internal ID renamed for the Desert Eagle pistols, for better inventory sort with other Desert Eagle pistols.
All handguns are now based from the vanilla equivalents, and inherit their data, instead of, say, the Colt 1911 copying the Beretta's data. This has the advantage that, if you have anything modifying the stats of the vanilla guns (ie: the Rebalance patches in this same pack) it will affect these too.
Spurious stat changes are removed where not justified. I think they may be leftovers from previous Anomaly versions? In any case pistols getting double the power or half the fire rate of the vanilla equivalents, having the upgrades from a different variant or gun, or using .45 silencers when being a 9mm gun, despite already having a sight or laser attached seemed ludicrous.
Fixed Sin trader file.
Parts fixed for those guns that had incorrect ones assigned.
Icon file trimm-actually no. It was impossible to get it trimmed and be DX8-9 compliant. So I've split the icons in different smaller files per pistol family. Now all these files weight less than half the original icon file.

Settings for actor effects, Grok's Enhanced Recoil, and Mags Redux changed and/or fixed to follow more closely the vanilla equivalents.

Integrated into:
Grok's Stash Overhaul
Lootboxes
PDA Interactive
Weapon Parts OVerhaul

----------------------------------------------------------
-Patches:

Luna's Master Dissasembly List and Parts Fix

Mags Redux Standalone
If you don't want any of the pistols (say because you don't want bloat in your game), this will add the following mags in the mod and nothing more.
	-FN57 Extended Magazine
	-PM Makarov Drum Magazine
They're not assigned to guns carried by NPCs, and must be bought.

You still need all files from the mod in the following directories with such names fully or partially:
gamedata\textures\wpn\pm_anomaly\   mag_pm_custom_9x18pm_84_lod0
gamedata\textures\wpn\57_anomaly\   tex_0057_2

Either disable everything in the original mod except the textures folder, or make a new MO2 "mod" with this patch and those textures.

----------------------------------------------------------
-Known issues:


wpn_fn57extended_mag.ogf
wpn_pmdrum_mag.ogf