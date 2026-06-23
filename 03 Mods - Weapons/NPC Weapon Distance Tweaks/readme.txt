-Module:
NPC Weapon Distance Tweaks

----------------------------------------------------------
-Compatibility:

----------------------------------------------------------
-Explanation:

Same idea as OnTuMuCT's Correct Weapon Distance:
https://www.moddb.com/mods/stalker-anomaly/addons/correct-weapon-distance-vanilla-bas-dltx

That mod settled the same max_radius values for pistols, SMGs, shotguns and 9x39 rifles.

This mod expands on that idea by covering weapons not only from vanilla and BaS but from many other mods, and having various sets of new values depending on weapon type and expected range:

Pistols:
Small caliber		= 75  (ie: 9x18)
Medium caliber		= 100 (ie: 9x19, 45 ACP)
Big caliber			= 150 (ie: 357)

SMGs:
CQC					= 50  (ie: Kiparis)
Short				= 100 (ie: Bizon)
Average				= 200 (ie: MP5)
Long				= 300 (ie: P90)

Shotguns:
Average				= 100 
Sawn offs			= 75  
Threaded			= 150 
Breach loaders		= 125 
Breach sawn off		= 50 
Breach threaded		= 175 

Rifles:
CQC					= 300 (ie: AK74U)
Short				= 400 (ie: AK105)
Middle				= 450 (ie: AUG)
Average				= 500 (ie: M4)
Long				= 700 (ie: FAL, most AKs)

Snipers:
Short				= 800  (ie: Karabiner 98, SVD, VSSK)
Average				= 1100 (ie: SVU, Remington 700, M24)
Long				= 1500 (ie: TRG, M82, L96A1)

LMGs:
Short				= 750  (ie: historical or shortened LMGs, or ones based in ARs)
Average				= 1000 (ie: RPD, M249)
Long				= 1250 (ie: PKM, M60, mounted weapons)

Explosives:
These will have both a maximum range and a minimum safety range.

Short				= 35  (ie: small grenades)
Long				= 45  (ie: big grenades)
Propulsed			= 400 (ie: grenade launchers)
Rocket				= 800 (ie: RPG7)

Small safety		= 20  (ie: offensive grenades, weak explosions)
Cautious safety		= 40  (ie: defensive grenades, strong explosions

Each of these values are set at the start of "mod_system_npc_weapon_distance_a_vanilla.ltx", then inherited by every weapon.
You can tweak these as you want there, and changes will be applied globaly in all files of the module.

Values might need to be fine tuned, please experiment and communicate issues.


----------------------------------------------------------
-Patches:

----------------------------------------------------------
-Known issues:
