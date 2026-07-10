Fixes relevant axe weapons that are no longer axes since the "foraging update" on Hypixel Skyblock
\+ some random misc changes since the "texture update" <-- stupid
## Requires [NoResourcePack](https://modrinth.com/mod/noresourcepack)
### Be sure to add a NoResourcePack whitelist to the items you want fixed


<img src="image1.png">
### Note: This only sets the texture target to the vanilla one, you can still use a regular pack that overrides the vanilla items.

Relevant weapons fixed:
- Halberd of the Shredded -> Back to axe
- Daedalus blade -> Back to Axe (both fragged and unfragged)
- Ragnarock -> Back to axe
- Blaze slayer daggers -> Material fixed (they don't change material between attunements anymore)
- Katanas -> Back to diamond sword (except Voidedge, that is a minecraft:iron\_sword)

You don’t need Firmament or any other mod that textures items based on SkyblockID anymore, since hypixel is now using the standard Components system from newer Minecraft versions.
Since the server forces its resource pack, you really just need NoResourcePack (assuming you already use this, since you also want a Axe fix). NoResourcePack is useful here because it sets the server-sent pack to the absolute lowest priority, even lower than vanilla by default. Since components look for custom namespaces in the server pack, you can use the mod’s priority override to jump above the server pack and swap in your own textures. You just have to whitelist (look for the NoResourcePack's keybind) the specific textures you want fixed, and they'll replace the server-pack assets directly rather than the "untextured" ones from NoResourcePack.


No longer requires firmament: still recommend [Firmament Mod Announce Remover](https://modrinth.com/mod/firmament-packet-fix) (a.k.a. firmament packet fix).
Said feature simply is not regular Fabric behavior, and its trying to mimic a already-undesireable forge feature, appart from being a privacy breach.
