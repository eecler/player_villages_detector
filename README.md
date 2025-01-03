# Player Villages Detector
Fabric-based library for identifying player-built villages. 

## how to use:
1. define player-built blocks (in a tag file located a resources/tags/blocks/player_built_blocks.json)
like this:
```
{
  "replace": false,
  "values": [
     "minecraft:bricks",
     "minecraft:diamond_block",
  ] 
}
```
2.  use `VillageDetector.isPlayerBuiltVillage(world, new BlockPos(x, y, z))` to check if a structure qualifies as a player-built village
