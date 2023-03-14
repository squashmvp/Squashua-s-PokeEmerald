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

Notes folder contains more specific information. Notes folder will/currently contain(s) all patches for this specific project. Use those patches to patch your copy of Pokemon Emerald to enjoy this decomped game. Just a heads up, different builds+patches will NOT be able to support the save file the game generates from playing previous/future patches, at least for now.

# CHANGES BY ME (SQUASHUA GONZALEZ)

## -GENERAL-

Different Starters

All Pokemon up to Gen 3 in Wild

Wild Pokemon Locations Adjusted (Legendaries in Wild)

Items (Locations, Heal Effects, All Should be Replaceable Now in Some Fashion)

Item Prices Adjusted/Raised

Changed Pickup Table

Shops Adjusted(More Varied Selection)

Changed Pokemon (Evolution Condition, Abilities(Replaced with Hidden or Changed if Hidden Unavailable), Learnsets (Very Specific Cases), Stats, Catch Rates, Safari Zone Flee Rates)

Gave More Wild Pokemon Items

Changed Moves (PP, Power, Accuracy, Effects)

Changed Trainer Parties(Gym, Match Call, Elite Four) and their AI's

Hold Effects for otherwise useless Trade Items

Decapitalizations

## -MECHANICS-

Added Devolution Mechanic and Devo Stone

Added Evolution by Specific Move in First Slot

Reusable Move Tutors 

### Features Pulled/Copied from Other Branches/Tutorials (Would like to label with authors) - All below work but only Minor Testing was done

Faster HP Drain in Battle - https://github.com/pret/pokeemerald/wiki/Faster-HP-Drain

Improved V Sync - https://github.com/pret/pokeemerald/wiki/Improving-the-WaitForVBlank-function

Fixed RTC - https://www.pokecommunity.com/showpost.php?p=10211666&postcount=155

Re-Use Repels - https://github.com/pret/pokeemerald/wiki/Prompt-for-reusing-Repels

Consecutive OoB Healing + Rare Candy - https://github.com/pret/pokeemerald/wiki/Repeated-Field-Medicine-Use

Remove Extra Save Confirmation - https://github.com/pret/pokeemerald/wiki/Remove-the-extra-save-confirmation

Delay Skip in Battles - https://www.pokecommunity.com/showpost.php?p=10266925

Instead of Asking to Stop learning a New Move, You'll be Asked to Continue Learning - https://github.com/pret/pokeemerald/wiki/Instead-of-Asking-to-Stop-learning-a-New-Move,-You'll-be-Asked-to-Continue-Learning

Remove Low HP Sound in Battle - https://www.pokecommunity.com/showpost.php?p=10246778&postcount=194

Show IV/EVs in Summary Screen - https://www.pokecommunity.com/showpost.php?p=10161688&postcount=77

Move Relearner as option in Party Screen - https://www.pokecommunity.com/showpost.php?p=10470602

Starting Money Increased from 3000 to 5000 - https://www.pokecommunity.com/showpost.php?p=9967852&postcount=4

Fast Poke Center - https://github.com/pret/pokeemerald/wiki/Speedy-Nurse-Joy

Can Reset RTC on Title Screen (B + Select + Left Arrow) - https://github.com/pret/pokeemerald/wiki/Enable-the-Reset-RTC-Feature

Option to Skip Intro - https://github.com/pret/pokeemerald/wiki/Option-to-Skip-Copyright-and-Intro

Chosen Player Character in Intro - https://github.com/pret/pokeemerald/wiki/Make-the-Person-in-the-Intro-Match-the-the-Save-File

Shifting to Pokemon Already in Battle Exits Shift Menu - https://github.com/pret/pokeemerald/wiki/Shifting-to-Pok%C3%A9mon-Already-in-Battle-Exits-the-Shift-Menu

### These haven't caused any errors in build but are currently untested in game

Wrong Save Type Error Screen - https://www.pokecommunity.com/showpost.php?p=10449518

Surf Dismount Ground Effects - https://github.com/pret/pokeemerald/wiki/Surfing-Dismount-Ground-Effects

Soot Sack Check in Bag similar to Coin Case - https://www.pokecommunity.com/showpost.php?p=10222284&postcount=178

Sitrus Berry Restores 25% HP - https://github.com/pret/pokeemerald/wiki/Update-Sitrus-Berry's-effect-to-Gen-4-standard

Increase Item Capacity - https://www.pokecommunity.com/showpost.php?p=10523495

Item Automatically goes to PC if Bag is full - https://github.com/pret/pokeemerald/wiki/Item-Automatically-Goes-to-PC-if-Bag-is-Full

Increased Money Capacity - https://github.com/pret/pokeemerald/wiki/Increase-money-limit

Feed Any Number of Pokeblocks - https://www.pokecommunity.com/showpost.php?p=10364627

Berry Trees No Longer Disappear - https://www.pokecommunity.com/showpost.php?p=10142996&postcount=63

Hold B to Surf Faster (MIGHT BE WRONG) - https://www.pokecommunity.com/showpost.php?p=10137446&postcount=59

2x Faster Daycare - https://github.com/pret/pokeemerald/wiki/Make-Daycare-Faster-at-Leveling-Pok%C3%A9mon

Latios & Latias Roamers - https://github.com/pret/pokeemerald/wiki/Allow-Both-Latios-and-Latias-Appear.

Get Rid of Battery Run Dry Error - https://github.com/pret/pokeemerald/wiki/Get-Rid-of-Battery-Run-Dry-Error-Message

Gen 8 Synchronize - https://www.pokecommunity.com/showpost.php?p=10097171

Perfect IVs While Breeding - https://www.pokecommunity.com/showpost.php?p=10449489

## What's Left?

Fishing Never Fails (NOT WORKING) - https://github.com/pret/pokeemerald/wiki/Fish-Will-Now-Always-Get-on-Hook

Trick House Doll Quiz (Update Answers to fit Item Prices)

Ability Spread (Check to see if ENOUGH Pokemon have Synchronize, etc.)

Individual Pokemon Learnsets

Battle Tower Trainers Decapitalization

Random Decapitalizations

Trainer Parties (Grunts, Admins, Bosses, Overworld Trainers that Don't want your Phone Number)

Trainer AI's

Wild Pokemon Encounter Bug? - https://www.pokecommunity.com/showpost.php?p=10376011

Check Pulled/Added Features

Title Screen Title Faded a Bit - https://gamer2020.net/?p=369

## CURRENTLY THIS PROJECT IS INCOMPLETE
