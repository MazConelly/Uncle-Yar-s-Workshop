-Module:
HD Inventory Icon Framework [TheMrDemonized]
https://www.moddb.com/mods/stalker-anomaly/addons/hd-inventory-icons-framework

----------------------------------------------------------
-Compatibility:

----------------------------------------------------------
-Explanation:

----------------------------------------------------------
-Patches:

Compatibility safety for unpatched items
This patch doesn't include actual HD icons.
When the framework is used to patch an item, the changes to any section (item) go downstream. Any daughter sections will appear messed up in some way, for example their icons looking reduced in size.
In some cases, removing their inheritances is required as they would also inherit the new icon and coordinates, messing them up.
For others, adding a "inv_grid_scale = 1" line to their sections is enough to solve this.

This patch cover these currently known cases:
	Vanilla weapons
	Boomsticks and Sharpsticks, BAS Extra Weapons, MWP, SWP, and AO3 Late Comers weapon packs.
	MTacWPack's AS Val Mod3
	STALKER 2 - M9 Bayonet knife
	More Melee Features
	New Gas Masks
	Pouches and more for Mags Redux
	Urban Tactics

Any actual patch for the framework should be able to override this through DLTX:
	mod_system_a_hdicon_safety_items.ltx

----------------------------------------------------------
-Known issues:
