-Module:
Outfit Attachment Overhaul [artifax]
https://github.com/ahuyn/anomaly-armor-attachments

----------------------------------------------------------
-Compatibility:
Make sure you use the last Github version of OAO.

----------------------------------------------------------
-Explanation:

Integration into:
Lootboxes

----------------------------------------------------------
-Patches:

DLTX distribution
It will exchange scripted methods of trader distribution for DLTX.
Though OAO's documentation doesn't say it, traders are clasified per faction as poor, ok, and quality, and the attachments distributed so. Except ecologists, who are given nothing. This patch respect that.

Vanilla exo outfits tweak
Something that isn't mentioned in Outfit Attachment Overhaul's documentation, is that exosuits and derivatives aren't allowed to carry armor plates. If that was it, I'd assume it's an intended balance decision. But it doesn't allow protoexos either, which makes me lean towards a mistake or a yet to be implemented feature; the added exoskeleton shouldn't be an issue for those outfits to carry extra plates.
This adds all exo outfits (protoexos, exosuits, and nosorogs) to the list of outfits allowed to carry plates. Do mind, depending on your mod list you may end up with unbalanced and unintended protections levels.

Powerful Attachments [Vorcheski]
PA says it works better with OAO, but some of its values overwrite the higher ones from OAO with lower ones (independently from load order as its a DLTX mod).
Values affected are additional_inventory_weight and additional_inventory_weight2 for frames and grids (base and improved) and improved camelback. I deleted those values to let OAO's prevail.

----------------------------------------------------------
-Known issues: