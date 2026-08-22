-Module:
Russian Ammo Expansion [No_data]
https://www.moddb.com/mods/stalker-anomaly/addons/russian-ammo-expansion

----------------------------------------------------------
-Compatibility:

Original mod not needed.

----------------------------------------------------------
-Explanation:

- DLTX'd the assignment of ammo to guns and mags, so that the ammo is simply added, instead of the whole selection overwritten. This should be more compatible with other mods adding their own ammo as well.
- Trimmed redundant configs code. All ammo was already inheriting from one or another, but still repeating the already inherited data. No big thing, but should be a tiny bit more efficient.
- The icon file has been trimmed a bit and split, to reduce filesize and leave less empty space in memory.
- Text edited a bit. Old/damaged ammo are tagged as such in the name text. There were also short names unused, so I've assigned them. It should help unclutter the inventory from excess text covering the icons when using something like Utjan's QOL mods.
- Integration into the vanilla task rewards system.
- The Mags Redux patch has been integrated into the main files. It's not going to cause trouble if the player won't use Mags Redux anyway.

Integrated into:
Arszi's Mutant Bleeding + Arszi's Mutant Bleeding Optimization Pach
Grok's Stash Overhaul
Lootboxes
PDA Interactive

----------------------------------------------------------
-Patches:

--Gun mods patches.
These patches will cover the guns in the respective mods. Support for Mags Redux is also provided, as RAE only provides supports for vanilla magazines.

-Replacers:
Individual patches for mods replacing vanilla guns.
-BaS Patch
DLTX conversion of the original patch, with added Mags Redux support.
-Simple / Misc. Weapon Pack
-RWAP
-Other mods
Blanket patch for just about almost every other modded gun I've found that could use the ammo.


--Bigger pistol round icons
Pistol ammo will occupy a inventory space of 2x1, instead of 1x1, like Cr3pis' icons do.


--Real life 9x19 7N31
he 9x19 7N31 is a speciality ammo for which only a few weapons are actually prepared to use it in real life: the GSh-18, MP-443 Grach, and PP-2000. The Gepard and the PP-90M1 too, if we had mods for them.
This patch will make it so all guns, vanilla and modded, follow the same limitation.
PLEASE UNDERSTAND_SatoruIwata.gif, this is not quite balanced for gameplay, as it makes an entire ammunition useless (or purely loot cash), unless you specifically choose to use those three weapons.
On the other hand, you may consider this an edge to use those weapons over others.
Do not use with the Arti's Ballistics patch below.


--Arti's Ballistics patch
It does two things:
-Adds crafting recipes for the ammo.
-Some of the ammo both RAE and AB provide are redundant: 9x18 7N25, 7.62x39 7N23 and 57-BZ-231 (the same as AB's BZ API if with a different name), and 9x39 PAB-9.
The ones in RAE are disabled in favor of AB, to prevent this redundancy.

Still need to properly integrate the ammo itself into AB.

----------------------------------------------------------
-Known issues:

DO NOT USE the files in the [ABANDONED] folder. They were intended as revisions of the internal IDs, but somehow only caused issues, cause unknown.