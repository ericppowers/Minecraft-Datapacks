# Datapacks Included

## Iron Golems Crush Stone into Gravel

- [X] Implement check for `minecraft:iron_golem` on top of `minecraft:stone`
- [ ] Change from hardcoded check for iron golems to check for entity_type tag `crushes_stone`
- [X] Add `minecraft:ravager` to entity tag `crushes_stone`
- [X] Add `minecraft:ender_dragon` to entity tag `crushes_stone` (because why not)
- [X] Add `minecraft:wither` to entity tag `crushes_stone`
- [ ] Change from hardcoded check for stone to check for block tag `crushes_to_gravel`
- [X] Replace `minecraft:stone` in `crushes_to_gravel` with `minecraft:cobblestone` for realism
- [ ] Replace `minecraft:cobblestone` in `crushes_to_gravel` with `minecraft:stone` for balance (no infinite gravel generators)

## Custom Dimensions

- [X] Test creation of custom dimension with custom dimension_type, including modified biome distribution
- [ ] Test combining biomes from separate dimensions (i.e., overworld, end, and nether biomes together in one dimension)
- [ ] Test creation of custom biomes and inclusion into custom dimensions
- [ ] Test custom world generation settings
- [ ] Test custom structure and feature generation settings



# Planned Features

- Recipes:<br>
      - Stairs and slabs can be re-combined into full blocks<br>
      - 2 slabs can be crafted from a single block<br>
      - Stair recipe forms more stairs (**keep lossy**)<br>
      - Trapdoor and button recipes produce more (**keep lossy**)<br>
      - Enchanted golden apples can be crafted by combining golden apples with enchanted books carrying treasure or highest level enchantments (e.g., Mending, Fortune III, Frost Walker II, Silk Touch, etc.)<br>
- Trades:<br>
      - Sweet berries and cactus can be obtained from wandering traders<br>
      - Fishermen sell nautilus shells at master level<br>
- Gameplay:<br>
      - Entities take a small amount of damage when on top of a stone cutter<br>
      - Using bonemeal on dirt blocks next to grass blocks will cause the dirt block to convert into a grass block<br>
      - Using bonemeal on dirt blocks next to mycelium will cause the dirt block to convert into mycelium<br>
      - Striders can be sheared to obtain string<br>
- Generation:<br>
      - Fossils can form in desert and badlands biomes (and variants)<br>
      - Oasis structure generation in deserts<br>
<br><br>
- [X] 2 logs directly into 16 sticks
- [X] 8 logs in chest pattern, directly into 4 chests
- [X] Nether wart blocks back into netherwart
- [X] Quartz blocks (all) back into quartz (use item tag `quartz_blocks`)
- [X] Sand drops from husks
- [X] Very rare chance of wet sponge dropping from guardians
- [X] Very rare chance of obtaining a heart of the sea from an elder guardian
- [X] Honey can be used in place of slime for any recipe that requires slime **except magma cream** (use item tag `convenience:sticky_crafting_materials`)
- [X] Rotten flesh can be cooked into leather at a furnace, or even faster at a smoker (or even slower at a campfire)
- [X] Cobblestone can be smelted directly into smooth stone at a blast furnace
- [X] Allow blackstone to be used in place of cobblestone for any recipe, including redstone components (use item tag `minecraft:stone_crafting_materials`)
- [X] Allow polished blackstone to be used in place of stone for redstone components that blackstone could not otherwise to used for (use item tag `convenience:stoney_crafting_materials`)
- [X] Paper, bread, shulker boxes, and other recipes can be crafted in a 2x2 crafting grid in an L-shape
- [X] Droppers can be converted into dispensers using a bow
- [X] Droppers can be converted into dispensers using string and sticks
- [X] Horse armor can be crafted
- [X] Name tags can be crafted
- [X] Wool and cobwebs can be unpacked into string
- [X] Mooshrooms drop - addition to their normal drops - either red or brown mushrooms
- [X] Anvils can be repaired one level using one iron block
- [X] A water bucket and a dirt block can be combined to form an empty bucket and 9 brown dye
- [X] Saddles can be crafted
- [X] Snow layers can be turned into snow blocks
- [X] Clay blocks into clay balls
- [X] New sources of white dye: nether quartz
- [X] New sources of light gray dye: phantom membrane
- [X] New sources of lime dye: scute
- [X] New sources of purple dye: popped chorus fruit
- [X] New sources of magenta dye: chorus fruit
- [X] New sources of red dye: crimson fungus, nether wart, redstone, red mushroom, spider eye, and sweet berries
- [X] New sources of cyan dye: ender pearl, heart of the sea, warped fungus
- [X] New sources of brown dye: brown mushroom and mud
- [X] New sources of black dye: bone, bone block, charcoal, coal
- [X] New dye combinations
- [X] Smelting red sand produces orange stained glass
- [X] Pillar blocks (e.g., quartz pillar) can be converted back into their base block (i.e., quartz block) using a stonecutter
- [X] Chiseled blocks (e.g., chiseled quartz) can be converted back into their base block (i.e., quartz block) using a stonecutter
- [X] Polished blocks (e.g., polished basalt) can be converted back into their base block (i.e., basalt) using a stonecutter
- [X] Add andesite, diorite, granite, stone, and smooth stone to `minecraft:stone_tool_materials`
- [X] Pigstep can also be obtained from charged creepers
- [X] Piglins are angered when the player opens or breaks any kind of container, including hoppers, hopper minecarts, droppers, and brewing stands, or when they break any form of worked blackstone, ancient debris, netherite blocks, or spawners
- [X] Sand and sandstone can be turned into red sand and red sandstone, respectively
- [X] Converted Drowned can rarely drop tridents and nautilus shells if killed by a player
- [X] Turtles can rarely drop scute when killed by the player
- [X] Silverfish drop gravel
- [X] Ender Dragon drops dragon head, dragon egg, and elytra on death when killed by a player (maybe work in Luck status effect for dragon head and elytra?)
- [X] Elder guardians drop sponge (rather than wet sponge) when killed by lightning