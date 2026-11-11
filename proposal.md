# Dungeons & Dragons Character Holder

## Repository
(https://github.com/CalvinK922/proposal)

## Description
The program will create and hold D&D characters for the user in order for use during, before, or after a campaign. This relates to media and arts because D&D is a common game many people play or want to get into and the first step is creating a character you resonate with and picking such choices can be difficult so this program might be of use.

## Features
- Creates D&D character
	- Will role stats, hold character name, level, race, and allow for self stat import. this happens through a prompt and a assort of question asked like whether they want randomized stats or to self import them
- Holder into a file
	- The program will record the information from the previous function into a json file so player has it for later use. the holder is a a list of things the user themself adds to be later transferred to a file for either later viewing or further editing.
- The user will be able to make multiple choices in order to get certain out comes whether it’s to delete a character, create a new one, add an item, etc. through a prompt asking from a list on the user to pick. 

## Challenges
- I will need to research file types to make sure Json is the best course of action 
- Potentially want to implement a way to add items how to do that cleanly.
- How to import images into the Json file so if people create an image of their character importation is possible 

## Outcomes
Ideal Outcome:
- That players can create character a view in a seperate file with the image they imported, items are showns with stats, and backstory included. 

Minimal Viable Outcome:
- Holds the characters with their name, level, stats, and race. Also Appears in Json file that allows people to still use the holder at a level of usefulness.
## Milestones

- Week 1
  1. Create the character creator function, adding the stats, items, modifiers applied, health.
  2. Potetially the item creator/importation, creates items, holds backstory, flavor text

- Week 2
  1. character holder, creates the list for each component and readies them for transfer to file type, also holds the ability to delete things within the holder.
  2. Item/ armor holder, creates the list for items with capabilities with edits and durability.

- Week N (Final)
  1. Creates the choices sequence for the player to be able to interact, with different options that make sense example asking the player the name of character they want to edit or delete.
