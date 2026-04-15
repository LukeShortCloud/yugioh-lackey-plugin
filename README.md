# Yu-Gi-Oh! Plugin for [LackeyCCG](https://lackeyccg.com/)

This is a modern fork of the original [Yu-Gi-Oh! plugin for LackeyCCG](https://lackeyccg.com/yugioh/) that was last updated in 2013.

----

**TABLE OF CONTENTS**

- [Changes](#changes)
    - [Breaking Changes](#breaking-changes)
        - [Existing Alternative Artwork](#existing-alternative-artwork)
    - [Non-Breaking Changes](#non-breaking-changes)
        - [Case-Sensitive File Names](#case-sensitive-file-names)


## Changes

These are changes between the LukeShortCloud fork and the original plugin.


### Breaking Changes

Existing decks may be broken with the changes listed here. Old and new card names are provided to help with the manual transition that is required by end-users.


#### Existing Alternative Artwork

The following changes have been made to improve existing and upcoming alternative artwork cards:
- Set changes. Alternative artwork cards are now listed from real sets instead of a fake "ALT" set.
    - Except for the Lost Art "LART" set.
- 1st edition artwork added. Some cards did not feature their actual 1st edition artwork.
- Unused card images have been removed. Some cards had two image files for the same card.
    - The best quality variant was kept.
- New standard for naming conventions.
    - "Alt Art NUMBER" describes which exact alternative artwork it is (some cards have more than one).
    - "Alt Txt NUMBER" describes the iteration of different effect text.
- Japanse artwork shown on English text cards has been renamed to "Uncensored". These usually from official Asian-English sets.
- Duplicate cards have been removed. If possible, cards with better readability have been kept.

| Old Card Name | New Card Name |
| ------------- | ------------- |
| Airknight Parshath (B) | Airknight Parshath |
| Ancient Gear Golem (B) | Ancient Gear Golem |
| Ancient Gear Knight (B) | Ancient Gear Knight |
| Ape Fighter (B) | Ape Fighter |
| Autonomus Action Unit (B) | Autonomous Action Unit |
| Axe of Despair (B) | Axe of Despair (Alt Txt 1) |
| Battle Fader (B) | Battle Fader |
| Bazoo the Soul-Eater (B) | Bazoo the Soul-Eater |
| Beast King Barbaros (B) | Beast King Barbaros (Alt Txt 1) |
| Big Bang Shot (B) | Big Bang Shot |
| Big Shield Gardna (B) | Big Shield Gardna |
| Blackwing - Zephyros the Elite (B) | Blackwing - Zephyros the Elite |
| Blizzard Dragon (B) | Blizzard Dragon |
| | Blue-Eyes White Dragon |
| Blue-Eyes White Dragon | Blue-Eyes White Dragon (Alt Art 4) |
| Book of Moon (B) | Book of Moon |
| Botanical Lion (B) | Botanical Lion (Alt Txt 1) |
| Call Of The Haunted | Call of the Haunted |
| Call of the Haunted (B) | Call of the Haunted (Alt Txt 1) |
| Card Guard (B) | Card Guard (Alt Txt 1) |
| Card Trooper (B) | Card Trooper |
| Chiron the Mage (B) | Chiron the Mage |
| Cyber Dragon (B) | Cyber Dragon |
| Cyber Dragon (Alt) | Cyber Dragon (Alt Art 1) |
| Cyber End Dragon (Alt) | Cyber End Dragon (Alt Art 1) |
| Cyber Jar (B) | Cyber Jar |
| Cyber Valley (B) | Cyber Valley |
| D.D. Assailant (B) | D.D. Assailant (Alt Txt 1) |
| Damage Gate (B) | Damage Gate |
| Dark Magician of Chaos (B) | Dark Magician of Chaos |
| Dark Resonator (B) | Dark Resonator |
| Dark Valkyria (B) | Dark Valkyria (Alt Txt 1) |
| Des Mosquito (B) | Des Mosquito |
| Doomcaliber Knight (B) | Doomcaliber Knight |
| Drillroid (B) | Drillroid |
| Ego Boost (B) | Ego Boost |
| Elemental HERO Avian (Alt) | Elemental HERO Avian (Alt Art 1) |
| Elemental HERO Burstinatrix (Alt) | Elemental HERO Burstinatrix (Alt Art 1) |
| Elemental HERO Sparkman (Alt) | Elemental HERO Sparkman (Alt Art 1) |
| Enemy Controller (B) | Enemy Controller |
| Exarion Universe (B) | Exarion Universe (Alt Txt 1) |
| Fiend's Sanctuary (B) | Fiend's Sanctuary (Alt Txt 1) |
| Fighting Spirit (B) | Fighting Spirit |
| Foolish Burial (J) | Foolish Burial (Uncensored) |
| Forbidden Chalice (B) | Forbidden Chalice |
| Forbidden Lance (B) | Forbidden Lance |
| Fortress Warrior (B) | Fortress Warrior (Alt Txt 1) |
| Gene-Warped Warwolf (B) | Gene-Warped Warwolf |
| Gilasaurus (B) | Gilasaurus |
| Goblin Attack Force (B) | Goblin Attack Force |
| Goblin Elite Attack Force (B) | Goblin Elite Attack Force |
| Gogogo Golem (B) | Gogogo Golem (Alt Txt 1) |
| Graceful Charity (B) | Graceful Charity |
| | Gyakutenno Megami |
| Gyakutenno Megami | Gyakutenno Megami (Alt Art 1) |
| Gyroid (B) | Gyroid |
| Half or Nothing (B) | Half or Nothing |
| Hedge Guard (B) | Hedge Guard |
| Helping Robo for Combat (B) | Helping Robo for Combat |
| Horn of the Unicorn (B) | Horn of the Unicorn |
| Hyper Hammerhead (B) | Hyper Hammerhead |
| Injection Fairy Lily (B) | Injection Fairy Lily |
| Kunai with Chain (B) | Kunai with Chain |
| Krebons (B) | Krebons |
| Luster Dragon (B) | Luster Dragon |
| Metal Reflect Slime (B) | Metal Reflect Slime |
| Miracle's Wake (B) | Miracle's Wake |
| Monster Reborn (J) | Monster Reborn (Uncensored) |
| Number 34: Terror-Byte (Alt) | Number 34: Terror-Byte (Alt Art 1) |
| Obelisk the Tormentor | Obelisk the Tormentor (Alt Art 1) |
| Obelisk the Tormentor (B) | Obelisk the Tormentor |
| Pitch-Black Warwolf (B) | Pitch-Black Warwolf |
| Pot of Duality (B) | Pot of Duality |
| Pot of Greed (B) | Pot of Greed |
| Power Frame (B) | Power Frame |
| Power Giant (B) | Power Giant |
| Premature Burial (B) | Premature Burial (Alt Txt 1) |
| Prideful Roar (B) | Prideful Roar |
| Reckless Greed (B) | Reckless Greed |
| | Red-Eyes B. Dragon |
| Red-Eyes B. Dragon | Red-Eyes B. Dragon (Alt Art 3) |
| Scapegoat (B) | Scapegoat |
| Shield Warrior (B) | Shield Warrior |
| Skill Successor (B) | Skill Successor |
| Slate Warrior (B) | Slate Warrior |
| Super Conductor Tyranno (B) | Super Conductor Tyranno |
| Tanngrisnir of the Nordic Beasts (B) | Tanngrisnir of the Nordic Beasts |
| The Tricky (B) | The Tricky |
| Toon Gemini Elf (B) | Toon Gemini Elf |
| Treeborn Frog (B) | Treeborn Frog (Alt Txt 1) |
| Twin-Headed Behemoth (B) | Twin-Headed Behemoth |
| Twin-Sword Marauder (B) | Twin-Sword Marauder |
| White Night Dragon (B) | White Night Dragon |
| Windstorm of Etaqua (B) | Windstorm of Etaqua |
| Zolga (B) | Zolga |
| Zombyra the Dark (B) | Zombyra the Dark |


### Non-Breaking Changes

Existing decks will continue to work as-is with the changes listed here.


#### Case-Sensitive File Names

The following card images have been renamed to work on Linux and macOS where case-sensitive file systems are used:
- AftertheStruggle.jpg
- ArcanaForceExTheDarkRuler.jpg
- ArcanaForceExTheLightRuler.jpg
- AttackAndReceive.jpg
- AttackReflectorUnit.jpg
- BarrelBehindTheDoor.jpg
- BeastOfTalwar.jpg
- BeastStriker.jpg
- BehemoththeKingofallAnimals.jpg
- BlastHeldByaTribute.jpg
- CallOfTheHaunted1.jpg
- CallOfTheHaunted2.jpg
- CeaseFire.jpg
- DZWChimeraClad.jpg
- DarkScorpionMeanaeTheThorn1.jpg
- DefenderTheMagicalKnight.jpg
- EarthboundImmortalAsllaPiscu.jpg
- EndymionTheMasterMagician.jpg
- ExileofTheWicked.jpg
- ExxodMasteroftheGuard.jpg
- FiendsHandMirror.jpg
- FruitsofKozakysStudies.jpg
- GaiatheFierceKnight1.jpg
- GammaTheMagnetWarrior1.jpg
- GearfriedTheIronKnight.jpg
- GoblinoutoftheFryingPan.jpg
- GokaThePyreofMalice.jpg
- HardSellinGoblin.jpg
- HardSellinZombie.jpg
- HelpingRoboForCombat2.jpg
- InvitationToADarkSleep.jpg
- LightOfIntervention.jpg
- MadolcheChickolates.jpg
- NinKenDog.jpg
- ObelisktheTormentor3.jpg
- OneForOne.jpg
- QueensBodyguard.jpg
- RainOfMercy.jpg
- RedArcheryGirl.jpg
- SephylontheUltimateTimeLord1.jpg
- ShadowOfEyes.jpg
- SoulsOfTheForgotten.jpg
- TheDragonDwellingInTheCave.jpg
- TheEyeOfTruth.jpg
- TheGiftOfGreed.jpg
- TheRegulationOfTribe.jpg
- TourGuidefromtheUnderworld1.jpg
- TributetoTheDoomed1.jpg
- UnleashyourPower.jpg
- WattKid.jpg
- WhirlwindWeasel.jpg
- WindEffigy.jpg
- YellowGadget1.jpg
- ZubabaBuster.jpg
- falchionb.jpg
- synchrodeflector.jpg
