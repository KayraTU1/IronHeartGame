[README.txt](https://github.com/user-attachments/files/24633391/README.txt)
PROJECT DOCUMENTATION: MYSTERY OF IRONHEART MANOR
1. Game Overview
Title: Mystery of Ironheart Manor Genre: Text-Based Mystery Adventure / Puzzle Language: Python 3 (Standard Libraries only)

Description: In this interactive fiction game, the player takes on the role of a paranormal investigator hired by Lord Kaldric. The objective is to locate the stolen "Aether Core" within a time limit of 6 in-game hours. The game features a randomized puzzle system, resource management (energy/batteries), and a branching narrative that changes based on the evidence collected and the player's final deduction.

Key Mechanics:

Dual Protagonists: Choose between Silas (The Eye - Visual clues) or Kaelen (The Ear - Audio clues/Lie detection).

Dynamic Puzzles: Safe codes and mini-game solutions are randomized at the start of each session to ensure replayability.

Navigation: A custom map system tracking the player's coordinates across 5 distinct locations.

Inventory System: Key items (Rusty Key, Secret Diary, Aether Core) unlock new paths and dialogue options.

2. Complete Walkthrough & Flowchart
Below is the step-by-step guide to progressing through the game and unlocking all 4 possible endings.

PHASE 1: Investigation & Gathering Tools
To progress, the player must first obtain the Key and the Clues.

Start: Select Character (Silas or Kaelen).

Move to Kitchen: go north -> go east.

The Riddle Puzzle:

Talk to Chef Gorn.

He asks for an ingredient with eyes that cannot see.

Answer: potato

Reward: Acquire Rusty Key (Unlocks Workshop).

Clue Obtained: Chef reveals the first 2 digits of the Safe Code (e.g., "48...").

The Safe Puzzle:

Go to Throne Room. Read the plaque description or use lens/listen.

Clue Obtained: Plaque reveals the last 2 digits (e.g., "...99").

Go to Library.

Unlock Safe with combined code (e.g., "4899").

Reward: Batteries (Restores Energy).

The Lore Clue (Crucial for True Ending):

In the Library, use search.

Item Obtained: Secret Diary.

Note: The diary reveals Lady Elara's true motive. Without this item, the "True Hero" ending is locked.

PHASE 2: Retrieving the Core
The player must solve the security system in the Workshop.

The Painting Clue:

Read the description in the Library.

Note the colors mentioned: "Blue tear, Red eye, Green grass."

Enter Workshop:

Move north from Hallway.

Door unlocks automatically if you have the Rusty Key.

The Lever Puzzle:

search the room. Choose yes to try levers.

Input Order: blue -> red -> green.

The Frequency Mini-Game:

A 4-digit number flashes on the screen briefly.

Memorize and re-enter the number correctly.

Reward: Aether Core (Main Objective Item).

PHASE 3: The Final Decision (Endings)
Once the Aether Core is in the bag, go to the Throne Room and use the command accuse.

🛑 ENDING 1: The "Bad" Ending
Condition: You accuse the wrong person (The Chef).

Input: Select Option 1 (Chef Gorn).

Outcome: The Chef is executed unjustly. The true thief escapes.

Status: FAILURE

⚖️ ENDING 2: The "Neutral" Ending
Condition: You accuse the thief, but miss the bigger picture.

Input: Select Option 2 (Lady Elara).

Outcome: You solved the crime. Lady Elara is arrested. Lord Kaldric gets his core back and continues his dangerous experiments that might doom the world.

Status: SUCCESS (Standard)

🚫 ENDING 3: The "Fired" Ending
Condition: You accuse the loyal servant.

Input: Select Option 3 (Butler James).

Outcome: Your deduction is wrong. Lord Kaldric fires you immediately.

Status: FAILURE

🏆 ENDING 4: The "True Hero" Ending (Secret)
Condition: You have the Aether Core AND the Secret Diary in your inventory.

Input: Select Option 4 ([SECRET] Destroy the Core).

Context: The diary told you the machine is evil. You choose to save humanity instead of obeying your client.

Outcome: You smash the core. Kaldric loses his power. The world is saved from the machine age.

Status: PERFECT COMPLETION
