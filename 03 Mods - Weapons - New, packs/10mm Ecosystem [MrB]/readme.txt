-Module:
10mm Auto Ecosystem [MrB]
https://www.moddb.com/mods/stalker-anomaly/addons/mrbs-10mm-auto-ecosystem/

----------------------------------------------------------
-Compatibility:
NOTE: You need the original mod for both Fixes, Lite, and Modular options.
You may disable the gamedata/configs and gamedata/textures/ui folders.

Arsenal Overhaul Late Comers:
It also has its own 10mm Auto features with ammo, parts, silencer, mags, and weapons.
While 10mm Ecosystem has more weapons and its own assets (models, textures, sounds), AOLC equivalent ammo compatible with Arti's Ballistics, a MP5SD-10, and is more lightweight by dint of using only vanilla assets.
For compatibility, you can use the Modular options except the Base folder, and let one mod overwrite the other, depending on what you prefer for the items that overlap.

----------------------------------------------------------
-Explanation:

Instead of a whole package, weapons can be selected by modules one by one. You can use these to customize your installation.
The Base folder is required for all of them.
Upgrade kits can be selected by separate.
Armor Modkits addon support is also integrated in case you preffer it to the upgrade kits or to control item bloat. Universal use mod kits will be used for the upgrades.


Implemented fixes for the mercenary traders that weren't implemented into the original mod, and could cause crashes.
Fixed upgraded weapons not having parts.
Fixed the MP510 Operative icon and reload sound issues.
Fixed the Bren Ten and Bren Ten SF texts being swapped.
Consolidated all NPC loadout files into a single one. I didn't test it yet but it should solve the issue of NPCs not carrying the mods's guns.
Consolidated all trade files as much as possible.
Consolidated all icons into one single file
Touched up the text a bit to reduce spacing.
To reduce the use of resources, all weapons will use their unscoped world model for all scoped instances (except the upgraded versions).
Integrated weapons into vanilla actor effects.
Reduced the value of the Kriss weapons. Jumping to +100k when the rest of guns in the mod go from 10k to 30k is pretty ridiculous.

Reworked distribution to NPCs:
-Guns should be rarer, only in the hands of veterans and masters. Veterans only get them with default ammo, and master with random configurations of addons and ammo.
-ISG, Mercs (main and ecolog), and Monolith remain the main users. All of them lack the Kriss Gen 1 and Tommy 10mm, and Monolith also the MP5/10.
-Freedom and Clear Sky become the secondary users, getting only basic versions of the weapons but barely no variants. Freedom gets the Bren Ten SF and Kriss Gen 2, and Clear Sky the P320 XTEN and the Banshee MkGs.
-Loners, bandits, and Renegades are terciary users, getting only the cheaper guns, and even then, veterans get the cheaper guns, and masters the more expensive ones. Shared guns are Kriss Gen 1, MP510, Tommy 10mm, and all Glocks 20 and 29. Loners also get the UMP10, Bren Ten and USP10. Bandits get the Kimber Eclipse and Renegades the Kimber Jagare.

Mags Redux support: now includes extended and drump magazines for MP510 and UMP10.
Tommy 10 mags can now be retooled to and from .45 ACP with the Tommy Gun Drop module in this package.

Integrated into:
Arszi's Mutant Bleeding + Optimized Patch
FireModeCheck
Grok's Stash Overhaul
Interactive PDA
Lootboxes
Weapon Parts Overhaul (now for realsies)

----------------------------------------------------------
-Patches:

Stats normalization
This patch will attempt to normalize the power and recoil of the weapons to vanilla standards.

Arsenal Overhaul Late Comers
This patch will help with consistency using 10mm Ecosystem and AOLC's 10mm Auto module.
Use this load order:
	1- AO Late Comers
	2- MrB's 10mm Ecosystem
	3- This module's Modular options, except the Base folder.
	4- This patch.
This will keep Ecosystem's icons and everything about the overlaping weapons with AOLC's MP5SD Whisperer and more finetuned version of the ammo. Mags Redux wise, the USP10 will use AOLC's purpose made mags instead of the XTEN ones.

.300 BLK Framework [Pillii]
Adds a variant of the Banshee MK10 in .300 Blackout, the Banshee 300 MK4. It can't be upgraded with the Operative or Enforcer kits though (for now).
It will be treated as a cheap option for .300 BLK, and carried by veterans at most.
If using the Modular options, you'll need the Banshee module.

----------------------------------------------------------
-Known issues: