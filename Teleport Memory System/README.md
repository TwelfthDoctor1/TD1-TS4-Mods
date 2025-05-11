# [TS4] Teleport Memory System

Have you ever have an issue where your Sim would skate or hike or jog but they would instead teleport or just quit the interaction completely due to them having a teleportation always enabled? This mod aims to fix these issues that Maxis have never thought of implementing.

The Teleport Memory System [TMS] is designed to implement and fix things:
It remembers your Sims current enabled teleportation through the form of a secondary trait (or memory trait). That memory trait will be used when the primary trait is removed or equipped when interactions like skating or hiking would run and stop.
It stops Sims from teleporting when doing certain walkstyle type component is involved (i.e. Skating, Hiking, Jogging, etc)
It allows for Sims to toggle the type of teleport system they wish to use (Choose from GoHereSuperInteraction and TeleportStyleSuperInjection)
It also fixes issues with the New Vampire Teleport System (Blame Maxis for not putting a testset distance in)

For example, when your Sim go to jog, the jog interaction run a loot action tuning to remove the teleport routing when that interaction starts and the teleport routing will return to the Sim when the interaction is completed or stopped.

Now you can enjoy hiking or skating or jogging without having to disable and enable teleportation.

Updated versions now stop Sims from teleporting with Delierate, when Possessed.

Another feature of this mod allows the Sim to enable or disable their current teleportation without touching the memory trait.

Next, as mentioned, Bat and Mist Teleport was modified by Maxis in Patch 1.68 to use the TeleportStyleSuperInteraction (or New Teleport Type). I'm sure many may have mixed feelings, but with this implementation, the teleport was slower.

[1.10 +] The Teleport Memory System is designed to allow preferences for the Teleport System for EACH type of teleport. With this feature, each teleport can use a different teleport system which can be useful in a bug with routing with platforms on different floors.

Should be mentioned that with the introductions of platforms, any form of routing to a floor/room with a platform will lead to Routing Failure. The workaround for this is to use any teleport with TeleportStyleSuperInteraction. Also, Vampire Run is affected by this as walkstyles uses GoHereSuperInteraction.

[1.10 +] As mentioned earlier, this mod fixes an issue regarding the Vampire Bat and Mist's TeleportStyleSuperInteractions for not having a testset distance to stop breaking interactions with certain objects such as the cauldron.

The TestSet distance to block teleportation is set to 1. If you wish to increase the distance, the tuning can be found in Teleport Memory System under TD1:testSet_Vampire_Teleport_Distance. If you want to use the distance used in the Transportalate, its 7 (I'd recommend not going into double digits, it will make it long range).

This mod supports the following teleports:
- Bat Teleportation
- Mist Teleportation
- Vampire Run (Not a teleportation but is inside for interaction fixes)
- Transportalate
- Dark Apparation (Part of Sage of Mastery Magic - Mastery Spells)
- Mist Teleportation (Part of Vampiric Teleport Spells)
- Bat Teleportation (Part of Vampiric Teleport Spells)
- And more, as introduced by the game

### First Time Usage

The following mods must be updated for the TMS feature to work for the following teleport systems (if you use those mods):
Sage of Mastery Magic + Mastery Spells + Ghost Butler + Alchemy [Version 1.63]
Allow Occult Interactions In Batuu
Vampiric Teleport Spells [Version 3]



For full description look here: [MTS](https://modthesims.info/download.php?t=649530)
