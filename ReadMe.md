# Sauropod Pack Current State Report:

### If you do any work with this mod I simply ask that you let me what you did so I can know how it lives!

## <span style="color:green">Ultimate goal of the mod:</span>
### New Dinos:
- Plateosaurus
  - Smallest sauropod
  - Walks on hind legs (except for sprint)
  - Front Claw attack only
  - Roar that stuns small dinos (Carno and smaller)
  - Two seater saddle
- Ampelosaurus
  - Anky on steroids
    - Harvest all the metal!
  - Huge damage resistance
  - Needs to be cannoned to torpor
  - Custom mushroom kibble to tame
  - Saddle is industrial grinder
    - Needs fuel to run
- Seismosaurus
  - Needs health dropped to 20% to tranq
    - adjustable in .ini 
  - Can damage metal with tail swipe
  - Can collect metals with foot stomp
  - On tame looses half health and 30% base melee damage
  - New taming food (Berry Jar)
  - Two saddles
    - Platform saddle
    - Factory saddle
      - Fabricator, smithy, chembench, and indi forge all in one
      - Requires fuel

### Remap of current three (all have slight mesh adjustments)
- Diplo
  - Saddle to three seats
    - Is smithy and mortar and pestle
  - Added tail and stomp attack
  - Base stats adjusted
- Bronto
  - New basic saddle with 5 seats
    - Crows nest seat has predator vision
  - Added front stomp attack
  - Base stats adjusted
- Titan
  - Adjust to level like all other dinos
    - High base stats but low gain per level (like Giga and Seismo)
  - Permanent tame
  - Breedable
  - Add railgun saddle

### Extras
- Crystal versions of all Dinos
- Custom spawn containers for:
  - Crystals
  - Seismo
  - Titan
  - This to keep wild spawns set and allow for more customization
    - .ini to control based on map (official maps only)
- New structures
- SP Smithy
  - Smithy with added bps
- Berry Vat
  - for cooking new recipes

## <span style="color:green">Current state:</span>
### New Dinos:
- Plateosaurus
  - Smallest sauropod
  - Walks on hind legs (except for sprint)
  - Front Claw attack only
  - Roar that stuns small dinos (Carno and smaller) - <span style="color:red">Sort of works but not fully as intended (currently wild dinos run after stun - not intended)</span>
  - Two seater saddle
- Ampelosaurus
  - Anky on steroids
    - Harvest all the metal!
  - Huge damage resistance
  - Needs to be cannoned to torpor - <span style="color:red">Unable to get this to work after multiple attempts of messing with the Rock Golem AdjustDamage graph</span>
  - Custom mushroom kibble to tame
  - Saddle is industrial grinder
    - Needs fuel to run - <span style="color:red">Unable to figure out implementation</span>
- Seismosaurus
  - Needs health dropped to 20% to tranq - <span style="color:red">this was working but then was messed up in a recent WC update. Started attempting to fix but was unable to finish.</span>
    - adjustable in .ini 
  - Can damage metal with tail swipe
  - Can collect metals with foot stomp
  - On tame looses half health and 30% base melee damage
  - Two saddles
    - Platform saddle - <span style="color:red">Currently there is a bug where pieces placed are spread out (not snapping right next to each other). Unsure what is the cause - no time to investigate</span>
    - Factory saddle - <span style="color:red">Unable to figure out how to hide crafting inventory unless Factory Saddle is equipped (i.e. Not showing when platform is on)</span>
      - Fabricator, smithy, chembench, and indi forge all in one
      - Requires fuel - <span style="color:red">Unable to figure out implementation</span>

### Remap of current three (all have slight mesh adjustments)
- Diplo
  - Saddle to three seats
  - Is smithy and mortar and pestle - <span style="color:red">Recently needed to adjust the placement of workbench mesh and unsure if this was fixed or not.
  - Added tail and stomp attack - <span style="color:red">for some reason tail attack direction, even though set as direction based, is completely random</span>
  - Base stats adjusted
- Bronto - <span style="color:red">same issue as diplo tail attack, have tried several mesh edits and don't like any of them... haven't had time to adjust back to original</span>
  - New basic saddle with 5 seats
  - Crows nest seat has predator vision
  - Added front stomp attack - <span style="color:red">for some reason this is targeting riders and not sure why or how to adjust</span>
  - Base stats adjusted
- Titan - <span style="color:red">Have not gotten to at all other than minor messing around</span>
  - Adjust to level like all other dinos
    - High base stats but low gain per level (like Giga and Seismo)
  - Permanent tame
  - Breedable
  - Add railgun saddle

### Extras
- Crystal versions of all Dinos
- Custom spawn containers for:
  - Crystals
  - Seismo
  - Titan - <span style="color:red">not done since Titan not done</span>
  - This to keep wild spawns set and allow for more customization
    - .ini to control based on map (official maps only)
- New structures
  - SP Smithy
    - Smithy with added bps
  - Berry Vat - <span style="color:red">people have been having issues with crafting, unable to find issue</span>
    - for cooking new recipes
