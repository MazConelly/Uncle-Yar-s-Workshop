-Module:
Russian Ammo Expansion [No_data]
https://www.moddb.com/mods/stalker-anomaly/addons/russian-ammo-expansion

----------------------------------------------------------
-Compatibility:

----------------------------------------------------------
-Explanation:

Three options are offered:
- 00 Original mod
- 01 Revised IDs
- 02 Arti's Ballistics

Option 00 only has fixes and additions. No further considerations.

Options 01 and 02 have the item's internal IDs renamed for better inventory ordering; I realize the original "russammo_" preffix was chosen to keep them together, but this way it should feel to "belong" more naturally among other ammo instead of standing apart.
Though this requires a new game if already using the mod in a save.

Option 02 was made for compatibility with for Arti's Ballistics. I only now realized both mods add the same ammo, so this disables what's already offered here to avoid redundancy and conflicts (which doesn't happen with the original "russamo" ID). These would be:
-9x18 7N25
-9x19 7N31
-7.62x39 7N23
-7.62x39 57-BZ-231 (the same as AB's BZ API if with a different name)
-9x39 PAB-9
It also has the Ammo Maker patch integrated, because AB uses the same craft system and items.
No actual compatibility with Arti's reworked system yet though.



All folders include the following additions to the mod:

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

These patches will cover the guns in the respective mods.
Support for Mags Redux is also provided, as RAE only provides supports for vanilla magazines.

-BaS Patch
DLTX conversion of the original patch, with added Mags Redux support.

-Simple / Misc. Weapon Pack

-RWAP

-Other mods
Blanket patch for just about every other modded gun I've found that could use the ammo.
A (non exhaustive) list:

Reworks/reanimations:
Blackgrowl: Better Bizon, Pretty Pistols Pack, PP-19 Vityaz Virilized, The AEK Kit
Firebreath: AUGmented

New guns:
Alex: AK107, Vulcan-M
ATHIS: AK103 BP, Calico M510, Groza custom, M4 Spectre, MK47, MP155, RPK16 drum.
Bert: Mauser C96, Sten
Beli fosfor: SIG Sauer P365
Billwa: DP27, IZH18 and MP18, MP40, Type 56 and 81 Rifles Pack
Blackgrowl: Sassy Ithaca, K-50M, MAT-49
Firebreath: ACE 52
JMerc: Luger P08, MP5K, MP9, TEC-9, Winchester Model 1887 Shotgun
Joseph Porta: Speedloaders and ammo for Revolvers
Khyber: S.N.I.P.S. - 9x39 Subsonic Network Integration Program for Stalkers
Kmack: Mosin Trio, Walther PDP, and Walther PPQ Q5 Match
Maid: Agram 2000
Pillii: Glock RONI, UDP-9
Pumkin0: Mosin & SKS stripper clips
Soulcrystal: Arisaka Quality Control, Benelli M4, FB Radom Vis 35
TheMrDemonized: BaS Extra Weapons
TheParazit: PL14

----------------------------------------------------------
-Known issues:
