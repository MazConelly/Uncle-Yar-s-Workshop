-Module:
NPC death outfit fix

----------------------------------------------------------
-Compatibility:

----------------------------------------------------------
-Explanation:
The death_outfits.ltx file determines how outfits are looted. Depending on the dead NPC's model, it will have assigned a particular outfit (and maybe a helmet) to be looted. It has a few issues though. Nothing that will break a game, just that some models won't drop their outfits. Some of such cases have been reenabled.

Other models don't have an existing player usable outfit, like the eco radsuit, so I simply assigned it the neutral variant as loot.

Some entries I haven't touched, as they have two different outfits share the same model. For example the merc basic and Ace SEVAs.