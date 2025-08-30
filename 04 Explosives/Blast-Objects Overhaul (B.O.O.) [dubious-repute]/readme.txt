-Module:
Blast-Objects Overhaul (B.O.O.) [dubious-repute]

----------------------------------------------------------
-Compatibility:
NOTE: You must disable the configs folder of the original mod.

----------------------------------------------------------
-Explanation:
DLTX conversion.

Also reduced size of icon texture, and made it completely compatible with vanilla by removing its dependency on TB's 475 New Stash Locations. Completely unnecessary, I'd say, as it changes the world model of the RPG IED for that of the explosives box; in fact, doubly unnecessarily as it used a copy of the model inside TB's mod, instead of using the one already in Anomaly; boggles the mind.

The default vanilla models are used by default instead. If you want new models, you can use Simple IED Models without worrying about dependencies or extras.

----------------------------------------------------------
-Patches:
Various mods will act as per BOO's rules, and grenades mods in general will use left click for long throw, right click for underhand pass.
Compatible with the original BOO, and both the DLTXd version here and the merge with Remote Controlled Explosives (also included in this patch pack).

Anomalous Mines: will also be throwable and treated as explosives instead of tools.

Urban Tactic: explosive charge still won't reach as far as grenades when thrown, and takes longer to explode.

Molotov Cocktail and Anomalous Grenades: will be thrown further for the underhand pass, for your safety, but you should still be careful and take cover fast.

Anomalous Grenades: it has a problem where it looks for a vanilla animation file that BOO overwrites to make grenades use the Gunslinger animation, making the game crash when equipping an anomalous grenade with the only message that it can't find a model file that it is very much where it's looking for. I did a sort of patchwork that I'm not happy about, but it's the most I'm able to do and should do the job. Anomalous Grenades will use the vanilla animation, but shouldn't crash anymore.

Flash Grenades Updated + Flash Mk2 Animation: only for the merge included in this patch pack.

You can also use the patch for Remote IEDs in my BCSI Patch pack to benefit of its recipes.

----------------------------------------------------------
-Known issues: