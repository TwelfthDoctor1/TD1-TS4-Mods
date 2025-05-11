# [TS4] Occult Hybrid Unlocker

The Occult Hybrid Unlocker & Stabilizer Mod, an amalagation of the former and IcedCream's Hybrid mod, aims to:

- Stabilize Hybrid Occults (as much as possible)
- Unlock Occult Transformations to have more than 1 occult
- Make Hybrid Occults workable in gameplay

## Stabilize Hybrid Occults

The mod will try its best to stabilize Hybrids, mainly through switching of occult forms, and CAS Edits.

Occult Sims will first switch to human form first (via on the fly command that is ran at start of interaction) and then transform into the respective occult.

As for CAS Editing, the mod will cache and remove occults prior to editinga nd will readd on Post CAS.

## Unlock Occult Transformations
Occult Transformation Interactions have been cleared of the occult tests to allow for Hybrid Sims, through transformation via normal means, such as the Rite of Ascension, Mermaidic Kelp, etc.

For other occults, you may make use of the Add Occult Function to add accordingly.

## Make Hybrid Occults Workable in Gameplay
The mod allows for Hybrid sims to switch through the Motive Panel to access the occult's Perks Panel, Orb Motive, etc.

Additionally, the Spellcaster and Fury Orb Motives will switch according to the selected Motive Panel/Secondary Form.

## Issues
I have verified that werewolf form is glitchy in several areas:

Facial Features (Bulgy eyes, glitchy ears, nose, etc). A remedy is to change the face of the werewolf in CAS.
Sim Posture when switching from Werewolf Occult to Vampire Occult (vice versa if affected) when using Secondary Form Changer. Switch to human form first before selecting the preferred secondary form.
Eyes will change colour on editing another occults secondary form, the only fix is to return and edit it. The eye option may be missing, but the options should appear after some edits/preset switching

## Installation
Simply place the mod package(s) and the TS4SCRIPT files into the Mods folder. Do note that script files can be placed no more than one subfolder deep (e.g. C:\User\Documents\Electronic Arts\The Sims 4\Mods\folder)

Depending on your preference, you can choose to include/exclude the following as per your gameplay needs:

- Phone Interactions (Adds the Occult Hybrid Interactions into the Phone)
- Permernant PlantSim
- PlantSim Interactions (Adds PlantSim options in the Occult Hybrid Interactions)
- No Thirst Need for PlantSim
- Servo Interactions (Adds Servo options in the Occult Hybrid Interactions)
- No Thirst Need for Servo

###### Tunings Modified:
- (7DF2169C-00000000-0000000000034E07) - testSet_NoOccult_Target
- (7DF2169C-00000000-0000000000034E00) - testSet_NoOccult_Actor
- (7DF2169C-00000000-0000000000034E09) - testSet_NoOccult_Actor_Tooltip
- (7DF2169C-00000000-0000000000034E0A) - testSet_NoOccult_Target_Tooltip
- (7DF2169C-00000011-0000000000025F60) - testset_Vampires_CanTurn
- (7DF2169C-00000011-0000000000025F62) - testset_Vampires_CanAskToTurn
- (E882D22F-00000015-00000000000348A5) - social_WitchOccult_RiteOfAscension
- (E882D22F-00000015-00000000000368C2) - mixer_Social_WitchOccult_RiteOfAscension_Offer
- (E882D22F-00000015-00000000000348A6) - social_WitchOccult_RiteOfAscension_Target
- (E882D22F-00000015-00000000000368C0) - mixer_Social_WitchOccult_RiteOfAscension_Request
- (E882D22F-00000015-000000000003686B) - Social_WitchOccult_AskHowToUseMagic
- (E882D22F-00000011-000000000002486A) - mixer_Social_VampireCreation_OfferToTurn
- (E882D22F-00000011-00000000000247D8) - mixer_Social_VampireCreation_AskToTurn
