-Module:
NPC_loadouts files rank fix

----------------------------------------------------------
-Compatibility:
Place this very early in your load order.

Don't use this with my BaS Lite files either; they also include these changes and you may risks errors and crashes.

Incompatible with NPC loadout overhauls unless they're patched for it..

Mods adding new guns may want to observe the new sections in case patching is needed.

----------------------------------------------------------
-Explanation:
The base vanilla npc_loadouts files have a couple of problems, I think. They're supposed to provide a pool of weapons based on faction rank of an NPC (novice, experienced, veteran, master) and whether they're main or secondary weapons.

However for many rookie ranks many secondary guns like pistols were treated like main weapons, the secondary weapon pool unused. It also means that any mod trying to add weapons and isn't aware of this problem might end up not doing anything. Now, rookies will have proper access to both main and secondary weapons, and mods may add their weapons properly.

Some factions share the same rank pool for rookies and experienced, mainly Mercs and ISG. I made an experienced pool for each and copypasted there the best guns from the rookie pool. Mods that look for such a experienced pool will now work correctly, though not other pools that vanilla doesn't use. If recommend pairing this with the weapon mods fixes also included in this patch pack.

Weapon entries for master ranks have also been simplified so that their ammo and attachments are always random, instead of several entries with different variables. Do tell if this cause any trouble for you

Also added "extra" sections to most faction ranks that lacked them. This makes easier for mods to add grenades to NPC loadouts.

The odd ranks (trainee, professional, expert, legend) are barely used most of the time. Some mods try to add weapons to them, and fail because of this. I may come back and enable them for proper use, but that may require some extensive balancing effort that I'm not sure I'm capable off

Proper loadout overhauls may not be compatible with these changes.


----------------------------------------------------------
-Patches:
Mods adding new guns may not work correctly without observing the new changes.

GRENATA expansion
Redistribution of vanilla grenades to all factions, as by default almost no one carried them. This will make the game harder, and defensive play against grenades users a more important aspect. If the words "Clear Sky Limansk" sends you into horrified screaming, don't use this. Though of course, you can tweak the file as you like for a reduced effect.

All experienced get RGD5 and all veterans get F1s. Army starts getting each at earlier ranks.

All masters have access to smoke grenades. Military factions start at experienced rank. Clear Sky, Ecologists, Freedom, and Monolith start at veteran.

All masters have access to thermite grenades. Military factions and Monolith start at veteran.


Anomalous Grenades patch
Master ecologists and Monolithians may carry any of the four.

Masters in CS, Duty, Freedom, and ISG may carry one particular type.

Traders will change similarly and require higher goodwill.

Note: Disable the gamedata/configs/items/trade folder in the original Anomalous Grenades.


Urban Tactics patch
Mere rework of the original file to work correctly.

Note: Disable the mod_npc_loadouts_urban_tactics.ltx file in the original Urban Tactics, or make sure this one overwrites it.

----------------------------------------------------------
-Known issues:
