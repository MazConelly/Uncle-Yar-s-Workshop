-Module:
Vanilla fire effects for mod guns

----------------------------------------------------------
-Compatibility:

----------------------------------------------------------
-Explanation:

Some mods, starting with BaS, use different flame and smoke particle effects when shooting a gun than vanilla guns do. Some people consider they cause lag. While there are mods to completely eliminate those effects from the guns, that seems a bit heavy handed.

The main option in this module will make weapons known to use these demanding effects to instead use vanilla effects.

Another option will disable all effects, including firing flash lights, from ALL weapons. This is intended for particularly weak computers.

The difference with other similar mods is that you can customize globally what's changed, by opening either of the mod_system_x.ltx files in notepad.

For example, all sniper weapons are given this section to inherit:

[vanilla_sniper_fire_effects]
flame_particles	= weapons\generic_weapon06
smoke_particles	= weapons\generic_shoot_00
grenade_flame_particles	= weapons\generic_weapon01
silencer_smoke_particles = amik\weapons\smoke_particles\silencer_smoke_particles_00

So if you like the improved flame particles, you can comment out that line by adding a semicolon at the start, like this:

[vanilla_sniper_fire_effects]
; flame_particles	= weapons\generic_weapon06
smoke_particles	= weapons\generic_shoot_00
grenade_flame_particles	= weapons\generic_weapon01
silencer_smoke_particles = amik\weapons\smoke_particles\silencer_smoke_particles_00

Any such change will trickle down to all covered sniper weapons.

In the case of the disabler option, the only section will look like this:

[disabled_fire_effects]
light_disabled = true
flame_particles	= 
smoke_particles	= 
grenade_flame_particles	= 
silencer_smoke_particles = 

Observe the added "light_disabled = true" line. That disables the flash light for all weapons; you can comment out the line, or change its value to false (though all weapons are already set to that, so it would be a redundant action).

----------------------------------------------------------
-Patches:

----------------------------------------------------------
-Known issues:
