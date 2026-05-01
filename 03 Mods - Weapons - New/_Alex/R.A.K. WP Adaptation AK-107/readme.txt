-Module:
R.A.K. WP Adaptation AK-107 [Alex]
https://www.moddb.com/mods/stalker-anomaly/addons/rak-weapon-pack-adaptation-ak-107-update

----------------------------------------------------------
-Compatibility:
NOTE: You still need the original mod. Install the options you want off it, disable the resultant configs folder, then picks from the options here as needed.

Read this docummente carefully. There's a lot of "well yes, HOWEVER" points in here.

This mod has A LOT of files and data. I may have lost track of mistakes I might have committed.

----------------------------------------------------------
-Explanation:


Holy moly maccaronni guano pants in head o ronni, Batman, what the absolutini jokerini. Never again.


All files have been split/simplified into: Main Files, Scope Kits, Scope mods & 3DSS, and MAS.

Files have been reworked so that it works like so:


- Main files:
All versions of the AK-107 with vanilla scopes and the Ranger version are included, along the upgrade kits.
3DSS configs are removed. Some scopes might lack crosshair textures; I think I didn't notice any odd one except for the Ranger's integrated one, but they could have escaped me. They could also crash; use these files with caution and report any issues.
The use of vanilla red sights have been disabled by default as well, as they crash in DX8-9 despite what the installer says.

Ranger variant given the wpn_crosshair_zf9 vanilla crosshair texture. I you think some other is better, do make a suggestion.

NPC distribution. The mod didn't distribute the gun anywhere except to Nimble and Meeker. Now you'll see it among the army and Duty traders, veterans, and masters. Nimble and Meeker will still sell the upgrades.
Corrected trade assignments. Most traders have five supply levels depending on goodwill. But unless you patch them, some don't: Nimble and Meeker only have two levels. So assigning them the gun and upgrades by level 3 only means they won't have any of the items.

Added default actor effects configs.

Integration into:
Grok's Enhanced Recoil
Grok's Stash Overhaul
Lootboxes
PDA Interactive.
Weapon Parts Overhaul


- Scope mods & 3DSS:
Choose the scopes you want. They're split by pack and author, so it should be easy to know which one you want/need. As above, 3DSS configs are removed.
Take all of them if you're using PUSSY, except Joseph Porta's; it'll need his "Optics and laser sights for firearms" mod.
Note: I haven't tried because of lack of time, but I assume the red dots issue still happens with these, so don't use them unless you play in DX11.

The 3DSS file will work for all files and scopes. I didn't touch any values, and I can't test 3DSS only than with the last update that attempts to avoid crashes for DX8-9 players, and the 3DSS configurations are supposed to be for the version in Gamma, which I can't test either, so I don't know if this works in vanilla. Don't @ me.
It will also reenable vanilla red dot sights.


- Scope Kits:
Scopes addons split off upgrade kits into their own file. This will require ALL scopes files. I ain't fuckin' with that many configs sections for now, fuck that noise. Nuh-uh. Not ever. No dice. Ya do eet.


- MAS:
Files converted into a single DLTX patch file.


- Base icon rework
42 MBs of icon file for ONE SINGLE WEAPON (even with four variants) is criminal. This is because the HD icons are included in the same file as the normal ones, and the scope kits multiply the icons by four.
This will trim the main icon file to 1 MB with only the standard icons.

And given I'm not bothering to work on the scope kits to ensure whether they can work on DX8-9, this won't cover them either.

Maybe you have an uberNASAiumcomputer and don't care. This isn't for you. Just skip this and keep using the full options in the mod's installer.


----------------------------------------------------------
-Patches:

TODO

Mags Redux
Offered separately because there's no 95-round drum magazine in base Mags Redux, and I copied the one in Mad's Overly Large Magazines.
To avoid duplicates if you have that mod as well, make sure to let Maid's files to load after this, or copy only the configs/magazines/weapons folder in here.


Armor Modkits addon
To control item bloat, this patch will remove the mod's upgrade kits and use universal modkits for the upgrades.
Given that the modkits act more under conceptual (that is, paint, replacement, custom, faction, or accesory) than fully personalized themes, there will be a progression of sorts. Note it won't be as straightforward as using a particular kit for each.

AK-107        + Specialized modkit = Ranger Ak-107
Ak-107        + Custom modkit      = Custom AK-107
Custom AK-107 + Specialized modkit = Raptor AK-107
Raptor AK-107 + Specialized modkit = Chaser AK-107

I may change the Ranger upgrade if I ever come up with a "camo" modkit, but there doesn't seem many mods that could make use of that.

----------------------------------------------------------
-Known issues:
