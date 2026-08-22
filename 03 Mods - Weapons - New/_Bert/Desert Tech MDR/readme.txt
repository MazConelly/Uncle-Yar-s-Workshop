-Module:
Desert Tech MDR [bert]
https://www.moddb.com/mods/stalker-anomaly/addons/desert-tech-mdr-pack
https://www.moddb.com/mods/stalker-anomaly/addons/mdr-reanimation

----------------------------------------------------------
-Compatibility:
NOTE: The original mod is still needed. Disable the configs folder

----------------------------------------------------------
-Explanation:

These rifles are supposed to be semi automatic. The 7.62 rifle will now act as so, though the 5.56 one is still allowed auto fire. This is mentioned in the descriptions.

Fixed the 7.62 rifle having an incorrect animation assigned for the aiming position. If you ever noticed the weapon dissapeared when aiming, this is it.

Consolidated files.
The Army won't sell the rifles (doesn't make much sense from what I see).
Traders won't sell rifles with Specter scopes already attached. This is for those who play without BaS scopes to avoid crashes when talking to vendors. You may still need BaS for the textures.

Icon file trimmed. The mod repeated icons over and over for each scope. This is a waste of memory, increasing the load of opening an inventory. I wonder where modders learned this from. *COUGH*BaS*COUGH*
I reduced the number and made liberal use of icon layers instead, something that even vanilla guns do. While some of the scopes I've checked seem fine (ie: ACOG), some others might have the icons misaligned, but it should be more performance friendly.

Integration into:
Armor Modkits addon. The mod includes upgraded versions of the rifle, but this requires a Special Upgrade Pack only available in Gamma (that I know). You can instead use a specialized kit from Armor Modkits addon.
FireModeCheck
Lootboxes
Grok's Stash Overhaul
PDA Interactive
Weapon Parts Overhaul

----------------------------------------------------------
-Patches:

MDR Reanimation
Auxiliary patch. Icon files made DX8-9 compliant.
This includes tweaks for the Mags Redux patch with the Lancer mag.

MDR Reanimation - 3DSS
Streamlining of the original configs files.
The unscoped upgraded MDR lacks the foregrip that the scoped models do, but has a PIP scope that the non-3DSS version doesn't have, and it doesn't even use the top red dot sight as an alt aim. So I swapped that for ironsights and gave it the fore grip.
Make sure to remove these files:
	mod_system_zz_3dss_dtmdr_black.ltx
	mod_system_zzzzzzzzzzzzz_3dss_dtmdr.ltx

----------------------------------------------------------
-Known issues:

The 3DSS reanimation has the original black opaque lenses meshes blocking the 3DSS'd meshes. Using MsPizza's 3DSS Lens Hider Hider is recommended.