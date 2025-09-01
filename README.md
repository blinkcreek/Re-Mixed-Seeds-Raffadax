# Re-Mixed-Seeds-Raffadax

**Required**
- [Re-Mixed Seeds by giovannim](https://www.nexusmods.com/stardewvalley/mods/22311)
- [Raffax Complete Production by Raffadax](https://www.nexusmods.com/stardewvalley/mods/8256)

This is a .json to add to \MixedSeedMod\SeedSets\ to add compatability with Raffadax. It is **incredibly** barebones. I play with "TrellisEnabled": true and "FlowersInFlowerMix": false so I didn't bother adding keys to specify trellis and flower crops. Additionally, **all crops share the same drop chance of 3.** 

In addition to the Raffadax.json, you'll also need to add this to \MixedSeedMod\config.json:

` 
{

"name": "Raffadax",

"UniqueID": "Raffadax.RCP",

"enabled": true,

"dropChance": 50.0

}

`

If anyone wants to add trellis and flower keys as well as adjust the drop chances feel free, I just figured this was better than nothing for now.
