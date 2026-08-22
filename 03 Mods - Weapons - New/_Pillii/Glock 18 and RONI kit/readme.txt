-Module:
Glock 18 and RONI kit [Pillii]
https://www.moddb.com/mods/stalker-anomaly/addons/pilliis-glock-18-and-roni-kit/page

----------------------------------------------------------
-Compatibility:
Note: The original mod is still needed. Disable the following folders:
	-gamedata/configs
	-gamedata/textures/ui

The following original options may still be used:
	-Non-BaS (it removes the LAM from the model for the improved carbine).
	-DX8-9 patch (it adds textures)
Disable the same folders as above as well, and keep the rest of assets they add.

IMPORTANT: If you were already using the mod, you'll need to start a new game.

Do not use the "Glock 18 and RONI kit" patch in the installer of Armor Modkits addon. It's not compatible with these reworked files.

----------------------------------------------------------
-Explanation:

wpn_glock_auto is the internal ID for the Glock 18, while there where three different IDs for the RONI:
-wpn_glock_roni for the standard version, which can attach various sights.
-wpn_glock_auto_roni_upkit is the version with a fixed lco1 sight and a laser pointer, that you only get using the upgrade kit on a Glock 18. Bit awkward, but Pillii admited it was his first foray into configs, so oh well.
-wpn_glock_pillii, judging by the text files, was supposed to be a "Glock 19 Gen4 Custom", but it was not a defined item, with no models usable for it, and added to mercenary loadouts, potentially causing a crash.

So the following has been done here:
-wpn_glock_pillii has been removed.
-wpn_glock_auto has been renamed into wpn_glock_18, and wpn_glock_roni to wpn_glock_18_roni, and wpn_glock_auto_roni_upkit to wpn_glock_18_roni_upkit. This has been done to make things easier (for me) to prepare the weapons and kits to interact as closely as possible. Also better ordering in inventory among other numbered glocks.
-The RONI upgrade kit (roni_upkit) has been cloned into a simpler kit (id: roni) that will get you the standard carbine set.

The improved RONI carbine will be now named "CAA Micro-RONI Gen 3 - PDF Custom", and mercs will rarely carry it.
Both versions of the carbine will be present in the RONI folder. You won't need the upgrade kits files for the PDF Custom, only to upgrade the base Glock 18.
Both carbines were missing missing sounds and animations; one version may be missing some that the other had. So I filled the gaps.
All weapons also had their push power reduced to the level of the vanilla Glock. They're all 9x19 weapons, the Glock 18's crazy fire rate should already be enough of an improvement.

The standard RONI kit will be sold by mercs, ISG, Nimble, and Sid. The improved RONI kit only by mercs and Meeker.

De-DLTX-fied files that didn't need to be DLTX.
Added short names.
NPC loadouts. Fixed faulty sections not existent in vanilla files. Recommended use of "NPC loadouts files rank fix" in this same package for full coverage.
Traders. Added the Glock 18 to inventories (they already sold everything else, why not the base weapon?). The files for the upgrade kit files have been fixed, as they affected no existing trader profiles.

Icon files made DX8-9 compliant (the original DX8-9 option only helps with the model textures, but its icon files are identical to the non DX8-9 compliant ones)).

New game loadouts file integrated into main files.

Integration into:
Armor Modkits addon
	You may use universal kits instead of the optional RONI upgrade kits. The custom kit will upgrade the Glock 18 to the standard RONI carbine, and the merc kit both the Glock 18 and the standard carbine to the upgraded carbine.
Enhanced Recoil - Gold Edition
GBOOBS
Grok's Stash Overhaul
Lootboxes
PDA Interactive
Weapon Parts Overhaul

----------------------------------------------------------
-Patches:

The Compensator, Non-BaS and 0.4 HUD patches in the original mod have been recreated.

Misc. Weapon Pack + Hisalute's Packs - Fixes and Tweaks
Requires both of "00 Main files - Glock 18" and "02 RONI" folders.
This patch will have MWP's Glock 18C use this mod's model, and its own version of the RONI carbine.
The 18C has an advantage over the 18 in fire rate, muzzle velocity, recoil control, and expanded magazine. Its rarity won't be touched, but the carbine will be a little more hard to find.
It will also use the PPP Sig 320 upgrade as Pillii's Glock 18 does, so it's not recommended to apply this patch in a current save with a Glock 18C already upgraded.
The Compensator option won't cover it, as the 18C already has an integrated one (the C stands for Compensated, yadda yadda).
NOTE 1: Currently only compatible with "Hisalute's Packs Repacked" at the moment. Make sure to pick the Glock 18C module.
NOTE 2: Despite the increased ammo load, the model will still use the normal 17 rounds magazine. I'm attempting to fix this inconsistency, but I'm not having much success with the animation working correctly.

----------------------------------------------------------
-Known issues:
