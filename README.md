# Fantasy

# Starlit Adventure
  
## A text-base game set in a fantasy world with elves, dragons, fairies, and more. You start in an unfamiliar location next to a sleeping dragon and end by placing the Skydrop on a pedestal in the Shadowforce Mystery Forest.
  
__On the way, you will collect:__
- Armor (goblin-made, dwarf-made, elf-made, and the legendary Lightstone Armor)
- Weapons (in a set with the armor, weapons and armor are found not in a set)
- Bottles (for putting all kinds of things in, similar to Legend of Zelda)
- Useful Items (grappling hooks, money, valuable materials, etc.)
- Pets (cats, dogs, a horse)
  
AND
- Random bits of information (locations, uses for items, help for the main quest, recipes, spells you can't use)

items
- grappling hook -- the text would read something like "there's a strange (structure) up there. there might be something useful too, if only you could reach the area."
- elf-made daggers -- the only thing that allows you to collect a dragon scale (the woodland dragon gives you a scale that it shed. you wond need an elf dagger until you find the next dragon)
- dwarf-made swords -- used for mining (dwarf swords would allow you to mine the Caotic Time Crystal, the only thing that can wake up the time dragon)
- Lightstone armor & weapon set -- Lightstone sword allows you to collect a time dragon scale. elf daggers cannot be used in this case. Lightstone armor allows you to hold the Skydrop. as there probably wont be combat in this game, it wouldnt reduce damage taken from anything, but it would also let you see into the surrounding area in dark places, like abandoned mines.
- bottles -- lets you hold a liquid, bug, or lizzard that someone wanted as part of a side quest. on completion of a side quest, you will get either money (to buy needed items) or info needed to complete the main quest.
- money -- lets you buy an elf dagger, dwarf sword, grappling hook, or bottle. when you complete a side quest that you need a bottle for, you give the NPC the bottle & contents. you can only have 1 elf dagger, 1 dwarf sword, and 1 grappling hook in your inventory.
- bug -- nondescript general bug. some people will want these in exchange for either info on money.
- lizzard -- nondescript general lizzard. some people will want these in exchange for either info or money.
- medicinal liquid -- general medicine. if given in a side quest, the NPC will give you more money than a bug or lizzard quest would get, or better info.
- recipe ingredient liquid -- general wet ingredient for a recipe. NPC who want this will give you the same amount of money, or the same quality of info, as a medicine side quest.
- flowers -- general flower. gets you the same things as a bug quest.
- mushrooms -- general mushroom. gets you the same thing as a bug quest.
- map -- used to find your way around Linnigin. without it, youre just aimlessly wandering.
- crystals -- can only hold 1 of each in your inventory at a time with the exception of the Warp Crystal. 2 Warp Crystals can be held and both are needed to get to the time dragon's island and back off.
    - White Crystal -- makes the light dragon friendlier and functions as a light.
    - Red Crystal -- makes the flare dragon friendlier and functions as a heat source.
    - Blue Crystal -- makes the river dragon friendlier and functions as a scuba set.
    - Green Crystal -- makes it harder to navigate a forest. would make the woodland dragon friendlier except the woodland dragon only appears at the start of the (x amount of days) cycle. also, the woodland dragon doesnt need to be friendlier.
    - Black Crystal -- makes the shadow dragon slightly friendlier. no extra effects.
    - Orange Crystal -- makes the sand dragon friendlier and helps to navigate in a sandstorm.
    - Milky Crystal -- makes the cloud dragon friendlier and functions as a GPS to find the cloud dragon.
    - Warp Crystal -- the only way to get on & off the time dragon's island.
    - Chaotic Time Crystal -- the only thing that wakes up the time dragon.
    - Placid Time Crystal -- makes the time dragon (and other NPCs) fall asleep.
- dragon scales -- each has a special effect. only 1 of each can be held in your inventory at a time.
   - Woodland Dragon Scale -- keeps inventory when the days cycle is repeated. dissappears after 1 days cycle restart.
   - Flare Dragon Scale -- makes NPCs (not dragons though) friendlier. NPCs will give you a better reward after you complete a side quest. dissapears when the day cycle restarts, even with the effect of a Woodland Dragon Scale.
   - River Dragon Scale -- has a calming effect on aggressive NPCs (even dragons). dissapears when used to freeze a body of water (there's no bridge across a river but you need to be on the other side). Woodland Dragon Scale's effect works on this.
   - Sand Dragon Scale -- makes a sandstorm that launches you into the cloudscape. dissapears after 1 use. Woodland Scale affects this.
   - Cloud Dragon Scale -- warps you to a specified location (not the time dragon's island though). Woodland Scale affects this.
   - White Dragon Scale -- illuminates the surrounding area and forces NPCs to tell the truth when giving you info. dissapears after a days cycle reset (Woodland Scale doesnt affect this).
   - Black Dragon Scale -- gives a speed boost in dark areas. White Crystal & White Dragon Scale cancel this effect. dissapears after you enter the light dragon's mines. Woodland Scale affects this.
   - Time Dragon Scale -- restarts the days cycle. dissapears after 1 use.
- Skydrop -- completes the game when placed on its pedestal. looks like a drop-shaped peice of the sky, only if it's day at the moment, the Skydrop looks like a peice of the night sky & vice versa.

commands (must be given in all caps or it will fail)
- ENTER (target area) -- target area must be in front of the player
- USE (item) -- uses up one item in your inventory. certain items cannot be used with this command, like Flare Scale, Woodland Scale, White Scale, Black Scale, all crystals except Chaotic & Placid Time Crystals & Warp Crystal, & Skydrop. armor & weapons are used with a different command & bottles can only be used with a CATCH command.
- GET SCALE -- uses elf dagger to collect a dragon scale after the dragon has given permission to collect one. can only be used if you have an elf dagger and permission to take a scale. can only be used on the time dragon if the command is GET TIME SCALE (must have Lightstone Sword to use GET TIME SCALE).
- MINE (target crystal) -- uses dwarf sword to mine a specified crystal. must have a dwarf sword to use this. can only be used on a Time Crystal if the command is MINE (Chaotic, Placid) TIME CRYSTAL (must have Lightstone Sword to use MINE TIME CRYSTAL).
- SEARCH FOR (target item) -- searches the are immediately around the player for a specified item. cannot be used to find a dragon or a scale, but can find the nearest town if you have a map (cant be veiwed in-game. just tells the computer that you can find the nearest town). only way to find bugs, lizzards, mushrooms, flowers, and crystals. if used to find a dwarf sword or elf dagger, will instead search of the nearest town that might have those.
- CATCH (target) -- uses bottle to catch a bug or lizzard. must have a bottle and have used the SEARCH command to find the target item.
- MOVE TOWARDS (target area) -- doesnt have to be in front of target area, just needs to have a map. can use it to get to a point where you can use the ENTER command, but without the map its pretty much just aimless wandering.
- REVIEW INFO -- logs something an NPC just told you.
- INFO -- gives bulleted list of all the things NPCs have told you. this list is not affected by a days cycle restart.
- TALK -- starts conversation with nearest NPC.
- BUY (target item) -- shopkeeper NPC will give bulleted list of shop inventory that looks something like
    - MAP 10 LINTS
    - BOTTLE 20 LINTS
    - MEDICINE (LIQUID) 40 LINTS
    - FLOWER 5 LINTS
  must have the amount of Lints (currency of Linnigin) to buy specified item. if
  you dont, the shopkeeper will tell you that you cant buy it because you dont
  have enough Lints.
- PLACE SKYDROP -- puts the Skydrop on its pedestal. must be in front of the pedestal to use PLACE command
