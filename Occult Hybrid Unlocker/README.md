# [TS4] Occult Hybrid Unlocker

This mod allows all Occult sims to become hybrids through normal means.
This mod originated from me trying to modify the Rite Of Ascension spell for other Occults to use them.

This mod requires at least two EP/GP that has an Occult. (Get to Work EP, Vampires GP, Island Living EP, Realm of Magic GP, Discover University EP)
After further testing, Mermaids MUST become a normal sim first before turning into a vampire.
This mod allows:

* Aliens to be Spellcasters
* Vampires to be Spellcasters
* Spellcasters to be Vampires
* Mermaids to be Spellcasters
* Servos to be Spellcasters
* Aliens to be Mermaids
* Vampires to be Mermaids
* Spellcasters to be Mermaids
* Spellcasters to be Vampires
* Aliens to be Vampires [Addon Only]
* Mermaids to be Vampires [Addon Only]

Sims that are in the process of transforming into a Vampire or Mermaid cannot ask to turn or be offered to turn (Not changed) or be casted upon using the 2 spells (Addon Only).

Currently, using this mod does not grant aliens to become vampires. I might have to dig further to find the source of the tuning that is blocking it.

Servos will not become mermaids and vampires, simply for the reason that they are bots. The best alternative they can do is to be a spellcaster. It is to be noted that Servo-Spellcasters cannot access their perks panel due to the Humanoid Occult (Servo) coming after Spellcasters. (Use cheats to unlock em)

Normal means referring:

Asking and Offering Rite of Ascension
Asking How to Use Magic
Ask To Turn into Vampire
Turn Into Vampire via Vampire Powers
Eating the Kelp and Going Into Water to be a Mermaid
I might post this later on MTS.

WARNING: Having Occults with secondary form to be mixed together may have undesirable results on the secondary form. CAS will also delete your secondary form. (Mainly for vampires, not sure of mermaids and aliens)

IMPORTANT NOTE: The needs panel, Perk Unlocker and Secondary Form will break or have issues, use mods linked above to fix them (Applies for Vampire-Spellcaster-Mermaid Occult Hybrids of any combination)


Addon Version (Requires RoM and Spellbook Injector):
The addon version adds 2 spells into the spellbook to turn sims into Vampires and Mermaids respectively. The spells can be cast onto your sim as well as other sims. These spells are helpful if you don’t want to find Vlad, Caleb and the Mermadic Kelp and would be essential for Aliens and Mermaids trying to become a Vampire.

The 2 spells are Rank 4 Untamed Spells (Master) and you can learn through duelling or through the sage. There are no tomes for the spells, sorry.

Note: Vampires cannot cast the Vampiric Transformation on themselves. Mermaids cannot cast the Mermadic Transformation Spell on themselves. Also, you can’t cast the 2 spells on the Grim Reaper.


Vampiric Transformation

Normal - Gives the first of three buff (Strangely Hungry) and turns in 36 hours

Charged -  Gives the last buff (Appetite Lost) and turns immediately or in 12 hours

Mermadic Transformation

Outcome - Gives the Strange Sensations Buff and lasts 24 hours

Failure of both spells gives the Buff: Consequences of Trying To Turn which has a +50 Dazed Moodlet and lasts 24 hours.



Conflicts & Issues:

This mod conflicts any mod that changes the following tunings listed at the bottom.

[Partial Conflict & Issue] Zer0′s Vampire Witches Mod - The end result for Ask How To Use Magic and the rest of the interactions leads Vampires to be Zer0′s form of Vampire-Spellcaster (not the actual hybrid that we are talking about)

[Workaround] Use the interaction Ask for Rite of Ascension on any spellcaster that knows the Rite of Ascension spell to become an actual Vampire-Spellcaster hybrid. I’d recommend that the all 3 sages should know of the Rite of Ascension spell as Maxis did not let the sages have it in their spellbook (If the sages know the spell, any sim can walk up to them, say hello and ask for the Rite of Ascension; that’s cheating and skips the fetch quest).

[Issue] (Those without RoM) Aliens and Mermaids Are Unable to Become Vampires - The Turn Into Vampire interaction will not work for Aliens and Mermaids is probably due to Maxis not downright showing the Option for the 2 occults. As for the Ask to Turn interaction, the interaction itself cancels out and the next section does not appear. Due to all this, I have to disable the 2 occult traits in the tunings.

[Workaround] Mermaids can turn themselves back into regular Sims by eating 2 Kelps and then turning themselves into Vampires (1.5 days) and once transformed, eat a kelp and walk into water to turn into a Mermaid.

Aliens, No sadly, you will have to use console to do so.

Tunings Modified:

(7DF2169C-00000000-0000000000034E07) - testSet_NoOccult_Target

(7DF2169C-00000000-0000000000034E00) - testSet_NoOccult_Actor

(7DF2169C-00000000-0000000000034E09) - testSet_NoOccult_Actor_Tooltip

(7DF2169C-00000000-0000000000034E0A) - testSet_NoOccult_Target_Tooltip

(7DF2169C-00000011-0000000000025F60) - testset_Vampires_CanTurn

(7DF2169C-00000011-0000000000025F62) - testset_Vampires_CanAskToTurn
