-Module:
NPC model protection fix

----------------------------------------------------------
-Compatibility:
Place this very early in your load order, and let any model overhaul like Fixed Vanilla Models and Textures overwrite it.

----------------------------------------------------------
-Explanation:
Technically, NPCs aren't protected by outfits the same way the player is. The player character equips an outfit object, which has different stats assigned, and the visual model file, and that's that. A NPC though is directly assigned the model file, bypassing the "equipping the outfit" step. That means they can't get those stats provided by the outfit. Instead, the model is assigned a configuration file in gamedata/configs/models/capture, which itself will reference a particular ballistic resistance scheme in the damages.ltx file. They also get a bonus for their rank, but that's not important here.

Some models look for the wrong capture file, so I changed them to the appropriate one. I only found four inspecting an unrelated matter. But there may be more. If you find any other or suspect about it, please do tell.