# Pokémon Emerald

This is a decompilation of Pokémon Emerald.

It builds the following ROM:

* [**pokeemerald.gba**](https://datomatic.no-intro.org/index.php?page=show_record&s=23&n=1961) `sha1: f3ae088181bf583e55daf962a92bb46f4f1d07b7`

To set up the repository, see [INSTALL.md](INSTALL.md).


## See also

Other disassembly and/or decompilation projects:
* [**Pokémon Red and Blue**](https://github.com/pret/pokered)
* [**Pokémon Gold and Silver (Space World '97 demo)**](https://github.com/pret/pokegold-spaceworld)
* [**Pokémon Yellow**](https://github.com/pret/pokeyellow)
* [**Pokémon Trading Card Game**](https://github.com/pret/poketcg)
* [**Pokémon Pinball**](https://github.com/pret/pokepinball)
* [**Pokémon Stadium**](https://github.com/pret/pokestadium)
* [**Pokémon Gold and Silver**](https://github.com/pret/pokegold)
* [**Pokémon Crystal**](https://github.com/pret/pokecrystal)
* [**Pokémon Ruby and Sapphire**](https://github.com/pret/pokeruby)
* [**Pokémon Pinball: Ruby & Sapphire**](https://github.com/pret/pokepinballrs)
* [**Pokémon FireRed and LeafGreen**](https://github.com/pret/pokefirered)
* [**Pokémon Mystery Dungeon: Red Rescue Team**](https://github.com/pret/pmd-red)


## Contacts

You can find those people on [Discord](https://discord.gg/d5dubZ3) and [IRC](https://web.libera.chat/?#pret).

This repository includes all of my changes to original code, some code by other developers, and that's it. The goal with this project is to overhaul the playstyle of the pokemon player through unconventional methods without compromising the pokemon spirit within them. My personal goal with this project is to develop a better understanding of decompilation in games. Changes below.

CHANGES BY ME(SQUASHUA GONZALEZ)
-GENERAL-
Different Starters
All Pokemon up to Gen 3 in Wild
Wild Pokemon Locations Adjusted(Legendaries in Wild)
Items (Locations, Heal Effects, All Should be Replaceable Now in Some Fashion)
Item Prices Adjusted/Raised
Changed Pickup Table
Shops Adjusted(More Varied Selection)
Changed Pokemon (Evolution Condition, Abilities(Replaced with Hidden or Changed if Hidden Unavailable), Learnsets(Very Specific Cases), Stats, Catch Rates, Safari Zone Flee Rates)
Gave More Wild Pokemon Items
Changed Moves (PP, Power, Accuracy, Effects)
Changed Trainer Parties(Gym, Match Call, Elite Four) and their AI's
Hold Effects for otherwise useless Trade Items
Decapitalizations

-MECHANICS-
Added Devolution Mechanic and Devo Stone
Added Evolution by Specific Move in First Slot
Reusable Move Tutors 

Features Pulled/Copied from Other Branches/Tutorials (Would like to label with authors) - All below work but only Minor Testing was done
Faster HP Drain in Battle
Improved V Sync
Re-Use Repels
Consecutive OoB Healing + Rare Candy
Remove Extra Save Confirmation
Delay Skip in Battles
Instead of Asking to Stop learning a New Move, You'll be Asked to Continue Learning
Remove Low HP Sound in Battle
Show IV/EVs in Summary Screen
Move Relearner as option in Party Screen
Starting Money Increased from 3000 to 5000
Fast Poke Center
Can Reset RTC on Title Screen (B + Select + Left Arrow)
Option to Skip Intro
Chosen Player Character in Intro
Shifting to Pokemon Already in Battle Exits Shift Menu

These haven't caused any errors in build and currently are untested in game
Wrong Save Type Error Screen
Surf Dismount Ground Effects	
Soot Sack Check in Bag similar to Coin Case MUST CHECK
Sitrus Berry Restores 25% HP
Increase Item Capacity
Item Automatically goes to PC if Bag is full
Increased Money Capacity
Feed Any Number of Pokeblocks
Berry Trees No Longer Disappear
Fishing Never Fails
Hold B to Surf Faster
2x Faster Daycare
Latios & Latias Roamers
Get Rid of Battery Run Dry Error
Gen 8 Synchronize
Perfect IVs While Breeding

What's Left?
Trick House Doll Quiz(Update Answers to fit Item Prices)
Ability Spread(Check to see if ENOUGH Pokemon have Synchronize, etc.)
Individual Pokemon Learnsets
Battle Tower Trainers Decapitalization
Random Decapitalizations
Trainer Parties(Grunts, Admins, Bosses, Overworld Trainers that Don't want your Phone Number)
Trainer AI's
Check Pulled/Added Features
