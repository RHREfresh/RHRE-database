# v142

## Game-Specific Changes

### Visual Effects
- Enabled noDisplay so it won’t be affected by Game Boundaries and other related features

### Extra Sound Effects
- Enabled noDisplay so it won’t be affected by Game Boundaries and other related features

### Sneezy Moon
- Adjusted earliness on "green sneeze - standalone - 3"

### Hop, Stop N Roll
- Fixed Deprecated ID for “hop”

### Alien Alphabet
- Added Deprecated IDs to sounds that were missing them:
   - alien - cha - uh
   - alien - cha - cha
   - alien - bom
   - friends - cha
   - friends - bom
   - friends - cha - adults
   - friends - bom - adults

### Owls
- Added a Base BPM and stretchability to the “ready?” sound
- Made the “parent - hoot” and “player - hoot” sounds stretchable and cut off at the end of the block
- Reorganized sounds slightly so that all the parent sounds come first, to be more in line with other call & response minigames

**Full Changelog**: https://github.com/RHREfresh/RHRE-database/compare/v141...v142

# v141

### Samurai Slice (GBA)
- Corrected the `gameOrder` value (previously 105, now 106)

### Monkey Watch
- Corrected the `gameOrder` value (previously 305, now 307)

## Game-Specific Changes

### Yum-Bot Simulator
- Fixed Deprecated IDs for the defective pudding patterns

### Sweeper Star 2
- Fixed Deprecated ID for “sweeping - constant - voice (no fade)”

### A for Effort
- Added the “aaaa” pattern

### Germ Aerobics
- Added Deprecated IDs to "wind-up - triple"

**Full Changelog**: https://github.com/RHREfresh/RHRE-database/compare/v140...v141

# v140

## General Changes
- **Rhythm Heaven Groove's main games have all been redone from scratch, with missing patterns/cues from the Dracobot pack added.**
- Some side games from Rhythm Heaven Groove have been added:
   - Rhythm Tweezers (Switch)
   - Who's Got Rhythm?
   - Bouncy Pufferfish
   - Swing
   - Owls
   - Can You Clap It?
   - Sensei Sparring
   - Skateboarding
   - Knock-Knock Quartet
   - Building Blocks
- All games now have brand new icons courtesy of Katie1118
- All games now have a `gameOrder` value, used to sort the games in the game selector by chronological order if the setting is enabled
- Games labelled as (Fever) or (Megamix) have been changed to be labelled as (Wii) or (3DS) for consistency with GBA and DS games

## Game-Specific Changes

### The Clappy Trio (All Versions)
- Renamed to "The Clappy Trio" (previously just "Clappy Trio")

### Fan Club (DS)
- Improved the earliness values in all 3 available languages
- Renamed patterns in non-english languages to use the non-english words for their sounds

### Karate Man (DS) (All Versions)
- Pot hit sounds have been changed to 0.5 beats long instead of 1 beat

### Karate Man (DS) (English)
- The non-pitch adaptive “punch-kick!” has had its syllables re-rendered to sound better at lower BPMs

### Fork Lifter (Base, 2 Players, and Remix 9)
- Added pitch randomization to the “pea - stab” sound

### Fork Lifter (All Versions)
- Added pitch randomization to the “pea - prepare flick” sound
- Redone pitch randomization on the “pea - flick” sound to be more game accurate

### Monkey Watch
- Redone pitch randomization on the “clap - onbeat” sound to be more game accurate

### Packing Pests
- Added pitch randomization to the “spider - out” sound

### Karate Man (Wii)
- Added tempo-based echo to most sound effects when possible to be more game-accurate
- Adjusted earliness on vocal cues
- All “punch” sounds are now 0.5 beats long
- Vocal cues have been renamed to reflect what they’re saying in each language
- Re-organized the folder structure to be cleaner
- Karate Man (3DS) is going to get a similar rework soon!

### Tongue Lashing
- Fixed a typo where “short red bug - teehee” was missing its hyphen

### Super Samurai Slice
- The sounds for the “big demon” pattern have been re-rendered to sound better at lower BPMs
- The following sounds now have pitch randomization:
   - big demon - blade
   - demon - appear - water
   - demon - appear - bush
- The following patterns have been added:
   - two demons - water - both
   - two demons - water - first
   - two demons - water - second
   - two demons - bush
   - three demons - water
   - three demons - bush
- The following patterns have been renamed:
   - demon from the water -> demon - water
   - demon from a bush -> demon - bush
- The patterns have been re-organized so that the most commonly used ones are first.

### Tangotronic 3000
- Added the "hand spring" sound for the ending twirl
- Added the “twirl (hand spring)” pattern
- Added Korean variant

### Pajama Party
- The following patterns have been renamed:
   - three -> three jumps
   - five -> five jumps
   - siesta -> lie down
   - random catch -> throw pillow - random catch
- The corresponding sounds for each of these patterns have also been renamed to match

### Kitties!
- Redone from scratch!
- Improved sound quality
- Added pitch randomization to the "clap twice - nya - appear" sound
- Added the missing second clap sound
- The "group spin" pattern now uses individual sounds for the spinning instead of a looped sound, being more accurate to the original game

### Karate Man (3DS)
- Pot hit sounds have been changed to 0.5 beats long instead of 1 beat

### Ninja Bodyguard (3DS)
- Added pitch randomization to the “shoot” sound

### The Dazzles (3DS) (Japanese)
- Adjusted earliness levels for the “san, shi!” count-in

### Sick Beats (3DS)
- Moved to the SIDE category

### Octopus Machine
- Added stretchable equidistant entities for squeeze, release, and pop

### Manzai
- Renamed from “Manzai Birds” to “Manzai”
- Fixed a typo with “aiteni aite na” being spelled “aichini aichina”
- Renamed “random boing!” to “random “donaiyanen!” phrase”

### Drumming Practice
- Improved sound quality
- Added the following sounds:
   - hit drums (no applause)
   - hit drum (intro)
   - show timing display
- Added the "hit drums (no applause)" pattern
- Added pitch randomization to the “hit drums” sound

**Full Changelog**: https://github.com/RHREfresh/RHRE-database/compare/v139.1...v140