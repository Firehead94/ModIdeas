ModIdeas
========

/* MineGen */
// Mechanics //
- Remove normal world gen for ores
- Create several types of blocks called "Stone" that have different drops + 1 "Cobblestone"
- Different drops refer to different types of ore NUGGETS with no more than 2 drops per stone + BaseBlock, also has chance to drop nothing
- Nuggets drop on a percentage base determined by YCoord
- - 0-12 
- -- 1%* chance to drop "Rough Diamond" [Requires lava near by or in a volcano type biome added by mods]
- -- 2%* chance to drop "Redstone Dust"
- -- 10%* chance to drop "Coal"
- -- 5%* chance to drop "Iron Nugget"
- -- 3%* chance to drop "Gold Nugget"
- -- 1.5%* chance to drop "Rough Emerald"

- - 13-16
- -- 0.5%* chance to drop "Rough Diamond"
- -- 10%* chance to drop "Coal"
- -- 1%* chance to drop "Redstone Dust"
- -- 1.5%* chance to drop "Rough Emerald"
- -- 3%* chance to drop "Gold Nugget"
- -- 3%* chance to drop "Iron Nugget"
- -- 1%* chance to drop "Lapis Lazuli"

- - 16-30
- -- 10%* chance to drop "Coal"
- -- 5%* chance to drop "Iron Nugget"
- -- 3%* chance to drop "Gold Nugget"
- -- 1.5%* chance to drop "Rough Emerald"
- -- 0.8%* chance to drop "Lapis Lazuli"

- - 30-65
- -- 10%* chance to drop "Coal"
- -- 5%* chance to drop "Iron Nugget"

- - 65-135
- -- 13%* chance to drop "Coal"
 
- Custom Dirt/Grass can drop Coal/Random Seeds/Coal (if underground) + "Dirt"
- Custom Sand can drop Salt/Seeds(Cactus?)/Bones(if underground)/Bone Meal + "Sand"

- Blocks placed by player do not have a chance to drop anything besides the base
- Trick WAILA to think my blocks are "Minecraft" blocks so you can't tell the difference
- Silk Touch wouldn't work on these blocks

// Processing //
- Gems need to be washed in a "Washer" to get "Washed <Gem Name>"
- "Washed <Gem Name>" need to be polished in a "Polisher" to get "<Gem Name>"
- Nuggets can be smelted in a "Smeltery" (Custom one or Tinkers Construct one)
- "Molten <Ore Name>" can be dumped/moved into "Press" to create "<Ore Name> Ingot"
- Nuggets can be ground into "<Ore Name> Dust Pile" on a "Grind Stone"
- 8 "<Ore Name> Dust Pile" can be crafted into "<Ore Name> Dust"
- "<Ore Name> Dust" can be placed in "Press" to create "<Ore Name> Ingot"

// Machines //
- "Washer"
- - Washes Gems
- - Products are "Washed <Gem Name>" + a byproduct
- - GUI
- -- Fluid Tank (Water Only)
- -- Input Slot
- - Will search for Hopper/Tube for output, if none found, will dump on floor

- "Polisher"
- - Polishes Gems
- - Products are "<Gem Name>" + 10% chance at "<Gem Name> Dust"
- -- "<Gem Name> Dust" can be placed in "Press" 
- - Manual Operation
- - Can be upgraded to powered if a power system is found
- -- I.E. [[Iron Gear, Conductance Coil, Iron Gear],[Transmission Coil, Polisher, Reception Coil],[Iron Gear, Redstone Capacitor, Iron Gear]] will give "Powered Polisher"
- - GUI
- -- Similar to AE GrindStone GUI

- "Smeltery"
- - Melts Nuggets/Ingot into 125mB/1000mB respectively
- - Can store max 10000mB
- - Can only hold 1 type at a time
- - Attach a "Drain" to dump into "Press"
- - GUI
- -- 1 Fluid Tank
- -- 4 Input Slots
- -- Button to Auto output to Drain (if found)

- "Press"
- - "<Ore/Gem Name> Dust" product is 1 "<Ore/Gem Name> (Ingot)"
- - "Molten <Ore Name>" will product 1 <Ore Name> Ingot"
- - Will search for Hopper/Tube for output, if none found, will dump on floor
- - GUI
- -- 1 Fluid Tank (4000mB)
- -- 1 Input Slot

- "Drain"
- - Fluid transport for molten metals

- "Tank"
- - Store excess fluids

*Percentage Drop values/Names aren't final, just expamples. Ability to add/detect modded ores as well.
