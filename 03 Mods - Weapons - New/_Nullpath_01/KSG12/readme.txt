-Module:
KSG12 [Nullpath_01]
Only available in the Gamma Discord.

----------------------------------------------------------
-Compatibility:
NOTE: You need the original mod. Disable the original configs folders.

----------------------------------------------------------
-Explanation:

Damage rebalanced to level with average vanilla 12 gauge shotguns.
Corrected the zoom_rotate_time stat. It will be used by the gun always, not only when attaching an ACOG.
Increased ammo count by one, from 14 to 15, just as the real gun (7 shells on each magazine tube, one readied).
Enabled alt aim, for whoever wants it. Copied from tweaks by Gaben.
NPC redistribution. Same factions (loner, Freedom, ISG, Mercs, Monolith), but higher ranks.
Trader distribution. Sold by the same factions that carry it (except loners), at medium-high goodwill.
Icon file trimmed.

Integration into:
Grok's Enhanced Recoil
Grok's Stash Overhaul
Lootboxes
PDA Interactive
Weapon Parts Overhaul
    
----------------------------------------------------------
-Patches:

KSG23
Asked by fleurtatious420 in the Anomaly Discord
Adds a KSG23 variant like the one in Gamma. It will be rarer, carried by master and legend ranks of the Army, Duty, Monolith, and Sin. Only the Army and Sin traders will sell it, and won't be found by Lootboxes or Grok's Stash Overhaul.
It requires either BaS, or the 23x75 ammo module in BaS Lite (you'll need the the patch for no BaS silencers).
Support for Armor Modkits addon allows you to change a KSG12 to the KSG23 yourself.

Simplified audio
The current audio implementation risks an issue: for some reason, shooting can cause some sort of delay that mutes all audio, including following shots, that only gets resolved until a different audio is played. This can be easily tested in the debug room.
If you find this issue, this patch will simplify the audio files, disabling the echo layers, shortening the length of the shooting sound, and making it mono instead of stereo, to prevent hearing NPCs shooting it from across the map. The sound is a bit weaker, but for some reason it solves the problem.

----------------------------------------------------------
-Known issues:

I added configs for a KSG25 variant, but I lack a model, and I don't think I can just tweak the KSG12 one for it.