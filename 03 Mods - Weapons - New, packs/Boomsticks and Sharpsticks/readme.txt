-Module:
Boomsticks and Sharpsticks [Mich]
https://www.moddb.com/mods/stalker-anomaly/addons/boomsticks-and-sharpsticks

----------------------------------------------------------
-Compatibility:

----------------------------------------------------------
-Explanation:

I've seen plenty of people say "BaS guns don't have any parts. Any mods for it?" But thing is, uh, BaS already assigns parts to its guns! But for whatever reason people end up not seeing them.

One possible situation could be overwriting. BaS has its own copy of the vanilla parts.ltx file with its guns added to it. In case some other mod overwrites it, this DLTX file should help ensure this doesn't happen.

Integration into the vanilla dynamic item spawn, reward, and stash systems.

Integration into:
Grok's Stash Overhaul
Weapon Parts Overhaul (same file as in WPO itself, but updated/touched up a lil bit, for example for correct inheritance of AUG and L85 quirks)

----------------------------------------------------------
-Patches:

BAS SR-2M Reanimated [Synd1cate] Fire position fix
by hoasd1
1) Set fire_point of all Veresks to "-0.002, 0, 0.14" as it was clipping through the weapon.
2) Fixed aim position of the "wpn_sr2_m1" and "wpn_sr2_m2" variants as it was away from the crosshair.

Honey Badger and .300 BLK Framework [Pillii]
Adds cloned variants chambered in .300 Blackout of several guns.
- Option 1 includes variants for the Steyr AUG A3 Commando and the Ruger SR556.
It will use the AUG mag in the Extra Mags patch above.
- Option 2 includes those in option 1 and the SCAR-SC. It's optional because it uses a modified SCAR-L model from BaS, with a shorter and wider barrel and different ironsights, and some people may not want more graphical assets. Also to maintain compatibility with BaS Lite.
If you use BaS Lite, you need either the basic Lite package alone, or with the SCAR-L module.

Disable 3D scopes
DLTX conversion of kda2495's addon. It will force the use of 2D scoping textures for PKA scopes and those weapons with integrated PIP scopes: AK5C with ISG kit, AUG 1 and custom, and SCAR-H Specialist Operator.
Use this if PIP scopes cause performance drops for you, or to avoid seeing certain weapons using those jump like crazy when shooting.

Knife skinning monkey patch
The vanilla item_knife.script file works out skinning, and it has a list of knives that can skin mutants, and another about which mutants are too hard for weak knifes. BaS has a copy including its knifes.
If another mod includes its own copy, you may not be able to use the BaS knifes anymore.
This allows you to bypass that issue. But it shouldn't be needed otherwise.

----------------------------------------------------------
-Known issues: