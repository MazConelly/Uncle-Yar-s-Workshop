-Module:
NPC loadouts files rank fix

----------------------------------------------------------
-Compatibility:
Place the main files early in your load order, but after BaS Lite if you use it.

Let the expansion and patches win all conflicts, including the the DLTX distribution patches in Uncle Yar's Workshop or Basic Trader Profile Expansion.

Incompatible with NPC loadout overhauls unless they're patched for it.

Mods adding new guns may want to observe the new sections in case patching is needed.

----------------------------------------------------------
-Explanation:
The base vanilla files for NPC loadouts have a couple of problems, I think. They're supposed to provide a pool of weapons based on faction rank of an NPC (novice, experienced, veteran, master) and whether they're main or secondary weapons.

However for many rookie ranks many secondary guns like pistols were treated like main weapons, the secondary weapon pool unused. It also means that any mod trying to add weapons and isn't aware of this problem might end up not doing anything. Now, rookies will have proper access to both main and secondary weapons, and mods may add their weapons properly.

Some factions share the same rank pool for rookies and experienced, mainly Mercs and ISG. I made an experienced pool for each and copypasted there the best guns from the rookie pool. Mods that look for such a experienced pool will now work correctly, though not other pools that vanilla doesn't use. If recommend pairing this with the weapon mods fixes also included in this patch pack.
Ecologist masters will now use the same pool of secondary weapons that eco mercs and ecologist experts use, instead of the dinky novice pool.

Weapon entries for master ranks have also been simplified so that their ammo and attachments are always random, instead of several entries with different variables. Do tell if this cause any trouble for you

Also added "extra" sections to most faction ranks that lacked them. This makes easier for mods to add grenades to NPC loadouts.

The odd ranks (trainee, professional, expert, legend) are barely used most of the time. Some mods try to add weapons to them, and fail because of this. I've added them properly to most factions, so those mods don't fail in adding their guns. Other than that, they just inherit the data of the previous rank. Maybe later updates will see more done to them.


Optional files for Weighted NPC Random Loadouts are available. These will trim the entries and assign a given weight to each weapon.


Proper loadout overhauls may not be compatible with these changes.

----------------------------------------------------------
-Patches:
Mods adding new guns may not work correctly without observing the new changes.


GRENATA expansion
Redistribution of vanilla grenades to all factions, as by default almost no one carried them. All ranks will have them, though in a progressive manner so that low end enemies don't grenade spam your position.

Even then, this will make the game harder particularly against higher rank hostiles. If the words "Clear Sky Limansk" sends you into horrified screaming, don't use this. Though of course, you can tweak the file as you like for a reduced effect.

All factions get RGF5 as novices and experienced, and swap it for F1 at veteran and master.
Novices have a small chance to have them, and the higher the rank, the higher chance they'll get them until masters get a guaranteed F1.
The Army starts getting each at earlier ranks at higher odds (easier, organized local access to trained professionals).

All veterans and masters have a 50 and 100% chance for smoke grenades.*
Military factions start at novice rank, though with very low chances.
Clear Sky, Ecologists, Freedom, and Monolith start at experienced, also at low chances.

All veterans and masters have a 15 and 45% chance of getting thermite grenades.
Military factions and Monolith start at experienced with very low odds.

*22-6-26 note: It seems the current versions of the modded exes have issues with NPCs using smoke grenades. As such, the lines adding them are disabled for the moment.


----The following patches are intended as auxiliary to the GRENATA expansion.

Anomalous Grenades
Master ecologists and Monolithians may carry any of the four types, at 10% chance each.
Masters in CS, Duty, Freedom, and ISG may carry one particular type, at 25% chance each.

Flash Grenades Updated
Most factions have a chance of getting a Zarya 2; 10% for novices, 25 for experienced, 50 veterans, and 75 masters. Duty and Monolith get an increased chance (+10%) and Army even more (25, 50, 75, 100 %s).
Freedom, mercs and ISG get the M84 and M-7290. They all get the M84 at a similar progression as everyone else with the Zarya. ISG get the M-7290 at the same rate, while Freedom gets a -20% and mercs a -10%.

M67 Grenade
Carried by masters, except loners, bandits, and renegades.
Monolith and Freedom start carrying at veteran.
Mercs and ISG start carrying at experienced.
WP factions get a 20% chance to get it, while NATO ones get a 40%; a higher rank gets a +10% bonus.
NOTE: Do not use the "More Common M67S" option with this.

Molotov Cocktail
Loners: novices get a 15% of getting a molotov, experienced get a 35%, veterans and master a 50%
Bandits: novices get 20%, experienced 40%, veterans and masters 60%.
Renegades: +15% over the bandits progression.
Sin: +10% over the loners progression.
Freedom and CS: they' more organized as the other factions, so they can just start using proper grenades earlier. They start at 20% at novice, and drop an additional 5% at experienced, veteran, and master down to 5%.

Stick Grenade
Carried by poor factions, and some of the solvent ones that don't follow any particular hierarchy as well: loners, bandits, Sin, and renegades.
Lower ranks will have modest odds of having the M24. Veterans and masters may carry the Splitterringgranate, but at lower odds. Sin and Renegades may have better odds than loner and bandits.
No one will carry the cluster, as its throw range is too short for the AI to use without killing themselves.

Urban Tactics
Veterans get a 50% chance for veterans to get the RDG-2 or the M18 (faction leaning depending), and masters a 75%.

----------------------------------------------------------
-Known issues:
