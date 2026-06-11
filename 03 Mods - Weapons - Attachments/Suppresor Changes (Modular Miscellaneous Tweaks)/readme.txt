-Module:
Modular Miscellaneous Tweaks - Suppressor Changes [Vintar0]
https://www.moddb.com/mods/stalker-anomaly/addons/modular-miscellaneous-tweaks

----------------------------------------------------------
-Compatibility:
Original mod not required.

----------------------------------------------------------
-Explanation:
DLTX conversion.

The original mod changes the stats of the basic "wpn_addon_silencer" template that all silencers inherit everything from, and removes changed stats from individual silencers.

Technically, all and new silencers, vanilla or modded, are covered by this as long as it inherits its data from "wpn_addon_silencer", but some silencers add their own stat changes, which would need to be squashed.

So, in addition to vanilla silencers, this conversion now also fully applies to silencers from:
-BaS
-MrB's 10mm Auto Ecosystem
-AO3 Late Comers
-Bert's M1 Garand
-Blackgrowl's AShey 'n ShAKky
-Joseph Porta's Vulcan
-Lewd's STG44
-Maid's Agram 2000
-Onerock's MCX Spear

There may be more I missed.


Quoting the original:

This changes how suppressors/silencers affect your weapon. Generally, they apply positive effects at the cost of increased maintenance. Thus, they are meant to be used by experienced STALKERs who can afford to pay the extra costs associated with them.

Adding a suppressor to your gun now applies the following:

+3% bullet speed
+1% gun accuracy
-18% hipfire recoil
-18% aimed recoil
+5% hipfire accuracy (stationary)
-5% hipfire accuracy (moving)
-15% hipfire accuracy (turning)
25% faster gun degradation (due to increased back-pressure and suppressor needing cleaning)

These are all easily editable in the .ltx file.

----------------------------------------------------------
-Patches:

----------------------------------------------------------
-Known issues: