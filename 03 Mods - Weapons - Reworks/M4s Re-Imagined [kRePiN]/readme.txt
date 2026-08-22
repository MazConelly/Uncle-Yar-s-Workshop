-Module:
M4s Re-Imagined [kRePiN]
https://www.moddb.com/mods/stalker-anomaly/addons/m4s-re-imagined

----------------------------------------------------------
-Compatibility:
NOTE: You still need the original mod. Disable its configs folder.

Updated for version 1.01.

Due to the way this was made, it will probably only work for the current, original release of the mod (at the time of writing) and probably not when/if updates.

The patch in MAScara is not compatible.

Do NOT use the patches in the installers for Arsenal Overhaul Latecomers or Armor Modkits addon..

----------------------------------------------------------
-Explanation:

This is a rework of the mod intended to make it compatible with other AR reanimations. Or if you want the new rifles as fully standalone weapons, not just replacers.
(Someone, somewhere, is chanting "Filler for the Throne of Filler! Bloat for the God of Bloat!")
If neither is your case, then you can ignore this whole module.


The M4A1 variants: Aeroknox AX-15, KAC URX, and SAI QD, become their own weapons, instead of replacing vanilla M4A1 variants. With these internal IDs:

wpn_m4a1_ax15
wpn_m4a1_urx
wpn_m4a1_sai

They're given the full patchment treatment as needed just like other modules: actor effects, mod integration... the works.

Given the vanilla camo M4A1 is carried and sold by Monolith and Sin, the custom by freedom masters, and ISG and merc vets and masters, and the Freedom by, well, ahem...
The AX-15 will be sold by mercs and Clear Sky, and carried by CS vets and masters, merc master, and, sometimes, by ISG vets and masters. 
The KAC URX will be sold by mercs and Monolith, and carried by vets and masters.
The SAI QD will be sold only by Freedom at the highest rank, and carried by Freedom masters.
Nimble can sell all of them.

The Vortex sight is also added to traders. Check with traders of those factions.

Files consolidated.

Scope icon file resaved into a proper .dds instead of .png.



Note: if you want to use a different reanimation for the M4A1 and M4A1 RAS, you can easily disable Krepin's by disabling the files:
mod_system_m4_krepin.ltx
mod_system_m4a1_krepin.ltx
Then place the other reanimation later in your load order. The model files for the AX-15, KAC URX, and SAI QD have been renamed to ensure compatibility.

Do note, this reduces the number of guns that can use the new Vortex sight to only those three (I tried to patch it for MAS but without success).


----------------------------------------------------------
-Patches:

Arsenal Overhaul Latecomers (.50 Beowulf module) + Armor Modkits addon
This patch allows to rechamber the (now standalone) rifles for .50 Beowulf ammo.
DO NOT use the M4 Reimagined patches in the installers for Latecomers or Armor Modkits, as those patches assumes the original replacing behaviour.

Modular Attachment System
This patch is incompatible with the patch in MASCARA.
Similar to the main files, if you only want the new variants, remove the files:
mod_system_z_k_m4a1_mas.ltx
mod_system_z_k_m4ras_mas.ltx

Modular Attachment System - Vortex sight
Converts the new Vortex sight to MAS.
Placed here temporarily until I can be bothered to update MASCARA, or Krepin takes it to update the mod.

----------------------------------------------------------
-Known issues:
