-Module:
.50 BMG ammo and Barret M82 restoration

----------------------------------------------------------
-Compatibility:
Incompatible/redundant with similar mods restoring the .50 BMG ammo.

Compatible with LEWD's .50 BMG Ammo Pack. Use the patch included in the "00 Vanilla - Weapons, ammo" folder.

----------------------------------------------------------
-Explanation:

Do note this isn't a "for fun" mod; the Anomaly devs presumably made the M82 chambered in 12.7x55 because otherwise it'd be the only gun using the .50 BGM, and it makes it harder to restock. You're warned.


This allows the Barret M82 to use .50 BMG ammo as normal, and restores the .50 BMG ammo. Other mods tried to do so but I remember them being clunky and/or merged with 4.6 ammo restorations. Not quite a fix patch, but not quite big enough to justify its own mod page.

The M82 should now hit harder, faster and farther than the rest of snipers and calibers, but not as the Gauss. You may see NPCs being pushed a few meters (in lieu of just becoming a big crater). The standard .50 BGM is craftable and distributed to some traders in very limited quantities (CS, Freedom, ISG, mercs, and Monolith).

In addition, being a NATO weapon, it will be assigned the NATO gas tube, not the Russian one.

The following mod weapons are covered by the same changes:
	-Blackgrowl's Barret M82A2
	-Chillcat's XM500
	-Lewdnatic's Desert Eagle in .50 BMG.
	-Sedzhimol's Gepard Model 6

You can loot the ammo from corpses, but do note that it remains highly scarce and it's not added to stashes, dynamic item spawns, or rewards. All this makes using the M82 a more difficult and focused task. It's overkill for the Zone after all.
That said, files have been made to integrate it into those systems. They're just disabled, as I'm unsure of how they'll affect the balance.
If you want to enable them, go to gamedata/configs/items/settings, and remove the .mohidden extension from the filename of these files:

mod_dynamic_item_spawn_ammo50bgmresto.ltx.mohidden
mod_item_rewards_ammo50bmgresto.ltx.mohidden
mod_treasure_manager_ammo50bgmresto.ltx.mohidden

Integrated into the vanilla looting, dynamic item spawn, and treasure, and task reward systems.

Integrated into:
Grok's Stash Overhaul
Lootboxes
Mags Redux. The M82 magazine will be changed to load .50 BMG by default instead of 12.7x55.
PDA Interactive

----------------------------------------------------------
-Patches:

Arti's Ballistics patch
The AP ammo is also craftable and added to traders at very high goodwill, with AB's new descriptions applied properly.
I left AB to set the stats, as I assume there's a game plan there. I may be wrong and the work it's simply incomplete; I'm not a ballistics guy, so feel free to mention anything that should be changed.

Barrel part
Adds a .50 BMG barrel part, and assigns it to all covered weapons.
Mostly made to screw around, you can skip this if you prefer not contributing to the item bloat.

----------------------------------------------------------
-Known issues:

For some reason the M82 tooltip only shows the standard .50 ammo, but that's not a big issue.