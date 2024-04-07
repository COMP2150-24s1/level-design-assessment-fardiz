[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Fardiz Khan
### Student number: 47818522 

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
What does the player learn? How does your encounter and broader level design facilitate learning in a way that follows good design practice?

Throughout the first section of the level, a few obstacles are placed in order to help teach the player mechanics. For example, a pool of acid is placed at the start of the section to teach the player the jumping mechanic, while afterward, there is a gun pickup followed by a small cave with a chomper and a spitter in it to teach the player to shoot at monsters, as well as introduce them to the enemy types. Throughout the rest of the level, obstacles and enemies are strategically placed in order to help guide the player in the right direction, while also leaving some room for exploration. For example, in the second section, there is a breakable column placed, which players cannot break without a staff, so this helps direct the player back to grab the staff. Players can also go straight to the final key door from the second section, but are then required to go back, as at that stage they only have two keys, and need to obtain the third key.

### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 

Throughout the entire level, there is curving intensity, with enemies and other items (health pickups, and checkpoints) being strategically placed to provide moments of intensity with points of relief in between to give players a chance to recover. For instance, in the first section, there is relatively low difficulty in order to allow players to get used to the game mechanics without being overwhelmed. There is then a small break before the second stage begins, where players are faced with significantly higher levels of intensity, where there is then another checkpoint and health pickup after getting through the second section to give players another opportunity for relief and recovery.The third section has another rise of intensity, as players are faced with more enemies and obstacles to obtain the final key, and then once they are able to obtain the final key, players are given another checkpoint and health pickup to get a chance to recover and get some relief once again, as well as save progress, before facing the final enemies to reach the ending key door.

### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?

There are challenges placed throughout the entire level, comprising of enemies (chompers and spitters), obstacles (such as spikes and acid) placed around the map in way where players are faced with significant challenge and then given a chance to recover their health and breathe a bit before facing the next challenge. Players are also rewarded for facing said challenges, as all the obstacles and enemies are placed to guard certain items, be it health pick ups, new weapons, or keys. The challenges players face throughout the level get more and more progressively intense throughout each section based on how far the players make it, starting off easy, and reaching a significant level of intensity by the end. Throughout the level, at the end of each of the sections, there are also checkpoints placed so players can save their progress, as well as health pickups placed after each major fight, giving players 2 health points back so that they can recover their health after losing a significant amount. There are also moments where rather than just fighting, players are required to find other ways to progress, such as moving a crate onto a pressure plate to keep a door opened, or using a movable box to kill an enemy from above.

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?

Obstacles and items are all strategically placed throughout the level to guide players in the right direction, while still leaving players some extra room so they are able to explore the map more in order to find more items that are required to further progress. For example, after the first section, the second section includes a breakable column, which requires players to go back to find the staff to break with. Once they get through the enemies and obstacles in the second stage, there is a health pickup placed to direct players to go up in that direction, which then leads players to the key door, which is blocked by another trigger door, where players realize that they only have two of the three required keys. This then directs players to go exploring the map more, to try and figure out where the third key is placed.

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Acid
Acid is introduced to the players in the first section, at the very beginning of the level, as a way to introduce the players to the game’s jumping mechanics and also to the way acid works.
### 2.2. Weapon Pickup (Gun) 
The gun weapon pickup is introduced to players in the first section, right after the acid, so that players can learn how item pickups work in the game, as well as to provide players with a weapon straight away, as they become crucial throughout the rest of the game.
### 2.3. Chompers
Chompers are also introduced to players in the first section, inside a small cave right after the gun pickup object, to introduce players to the way the chomper works, as well as to the game’s shooting mechanic.
### 2.4. Spitters
Spitters are introduced to the player simultaneously with chompers in the first section, in the cave. This way players are introduced to the two different types of enemies in the game, as well as the shooting mechanic
### 2.5. Checkpoints
Checkpoints are introduced to the player after the cave with the enemies, at the end of the first section, so that players are able to save their progress before beginning the next section, where the intensity rises significantly.
### 2.6. Moving Platforms
After the checkpoint at the end of section one, a moving platform is placed in order to transition players to the second section, as well as show them the timing of moving platforms.
### 2.7. Spikes
Spikes are introduced to players at the beginning of the second section - after jumping off the moving platform and fighting the first spitter, there is a small hole with spikes at the bottom that players must jump over.
### 2.8. Health Pickups
Health pickups are introduced to players after the first wave of enemies in the second section, so that players can recover their health after fighting the chompers and spitters that are guarding it and also prepare to fight the next wave of enemies.
### 2.9. Keys
Keys are introduced to the players in the second section, where after fighting the enemies, they are able to pick up the first and second keys for the final key door. This also introduces players to the key inventory in the top-right corner.
### 2.10. Weapon Pickup (Staff)
The staff weapon pickup is introduced to the players in the second section after the first wave of enemies, where players must go into a small cave and pick it up, and then there is a breakable column to introduce players to the staff mechanic.
### 2.11. Passthrough Platform
Passthrough platforms are introduced to players near the end of the level in the third section, where players are required to use a passthrough platform to jump over a large gap to get to the final key.
## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.

In my case, I had the idea for how my level was set out planned from the very beginning, so the main structure of the map was not change too significantly. Despite this though, throughout the creation of my game, iterative design played a crucial role, as multiple fixes and adjustments were required to be made to my level design to make the gameplay an enjoyable and challenging experience. This took me several playthroughs of the game, and minor adjustments after each playthrough. The first section of the level initially just had a pool of acid to teach players the jumping mechanic. After an initial playthrough, it was decided to add a cave to the game, in which the player would fight a chomper to learn the shooting mechanic. After playing through again, I decided this would be a good opportunity to also introduce players to both enemies, so a spitter was also added. The cave’s design was also slightly altered as it was discovered that players could climb over the cave and avoid the enemy completely. After this, I began work on the second section, where players were faced with the main challenge of the level. This section of my level did not undergo too much change in terms of structure, but after multiple playthroughs, it was decided that the section was not challenging enough, so more and more enemies were added, as well as obstacles such as spike pits. It was also decided that this would be where players can obtain the staff, and break the breakable column, and reach the second checkpoint. After another playthrough, it was found that the player lost a significant amount of health in this section, so a health pickup was added. It was the third section that underwent the most iterative change. Originally the third section consisted of just the cave with a trigger door, and a key, and the final key was in the final door room. It was decided that this did not allow for enough exploration, and made the level too easy, so I decided to add more behind the cave, so that players would attempt to leave the level and realize they didn’t have the final key, as I decided to move that to end of the newly added part of the level. This required players to explore more of the level to find the final key. It was decided it was still a little bit too easy, so for added intensity, chompers and spitters were added to the final door room, which I also decided would be blocked off by a trigger door that only opens when the final key is collected.

## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: ChatGPT
**Nature of Use** Finding relevant design theory.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to try and find some more relevant design theory that I could apply to my game. After googling them, however, I found most of them were inaccurate, and some didn't exist. One theory mentioned, however, was useful, and I've incorporated it into my work.

### Tool Used: Example
**Nature of Use** Example Text

**Evidence Attached?** Example Text

**Additional Notes:** Example Text


