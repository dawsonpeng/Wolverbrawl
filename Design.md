# Wolverbrawl

https://drive.google.com/file/d/1uumTLeGO2j_zCUp5YPlQZ1Gjpk0URRjP/view?usp=sharing 

---

## Overview

Wolverbrawl is a 3v3 multiplayer 2D pixel-art game inspired by Brawl Stars, themed around Harvard-Westlake. Players choose unique characters and compete in fast-paced, team-based game modes.

**Platform:** Laptop / PC

**Controls:** WASD and mouse

**Art Style:** 2D pixel art

**Match Length:** Short, high-energy matches (a few minutes each)

Heavy inspiration from Brawl Stars

Harvard-Westlake campus, culture, and faculty as thematic elements

**UI/UX:** pixel based, colorful UI/Buttons

**Menus:**
- Load into the main menu, displaying a selected character in the middle. buttons on the botttom to play, shop, friends/party, characters.
- Play- shows a menu with all the gamemodes to play. clicking play will start matchmaking with the character selected
- Shop- to roll for new characters/ maybe microtransactions
- Friends/Party- add friends and add them to your party to play with them
- Characters- shows all owned characters, clicking into each one allows you to upgrade it, unlock abilities, and select it for play

---

## Core Gameplay

3v3 multiplayer battles

Choose a character with unique abilities and stats

Fast rounds focused on teamwork and strategy

**Target Audience:** Primarily students who enjoy competitive and casual fast paced multiplayer games

---

## Game Modes

### Elimination
- First to two wins style. Each player has 1 life. First team to lose all players is eliminated and loses. If characters die at the same time, call it a tie and continue.

### Protect the Student
- Each team has a student taking a test. Opposing teams damage the other team's student. Teams must defend their own student while disrupting the enemy's. The student has a health bar, the first team whose student's health bar reaches 0 loses. There will be a 5 minute timer. If neither team loses, the one with the highest student hp wins.

More modes planned

**Fog:** every game will have a shrinking border from fog that does damage to the players to limit match time and remove ties. The fog should take 5 minutes to reach the middle.

After each game, a screen will be shown with kills/deaths/damage. Also an MVP with a formula to calculate it.

---

## Maps

Less detailed layout example for lounge:

<img width="333" height="469" alt="Screenshot 2026-01-12 at 8 19 57 AM" src="https://github.com/user-attachments/assets/eb6737ea-db11-43d0-b19e-f2088a2d6714" />

Maps inspired by Harvard-Westlake locations

Designed to encourage strategy, positioning, and team play

---

## Animation & Art

**Characters**

Quick, simple character designs

Each character has unique moves and stats

Characters inspired by HW culture and faculty

**Example:**

Mr. Theiss — throws chocolate at enemies

---

## Progression System

Gain and lose trophies based on performance. Matchmaking will be based on character trophy level.

Players gain trophies for each individual character they own, with an account trophy amount that is equal to the sum of all the trophies of individual character.

**Earn resources by playing:**
- Coins act as currency for upgrading characters. Upgrading characters increase their stats.
- Assignments act as a currency for unlocking character abilities(moves). Moves cannot be unlocked untill reaching a specific level.
- Gems are for the gambling system.

**Characters:**
- Unlock teachers via a gambling-style system (loot-based dopamine mechanics)
- Use gems to gamble, 2.5% chance of receiving a character, otherwise get random amounts of coins or assignments.
- Characters cannot be repeat.

<img width="570" height="582" alt="Screenshot 2026-01-12 at 8 19 31 AM" src="https://github.com/user-attachments/assets/832b35b7-9daf-4627-be6b-db8231aef21c" />

---

## Technical Notes

2D pixel-art rendering

**Modular character animation system:**
- Sprite sheet–based animations
- OR
- Characters built with separate components to move with coding:
  - Head
  - Body
  - Hands
  - Legs

Choice of artistic and technical animation work, sprite sheet preferred, however due to artistic and work time limitations, the other might be nessecary.

**Controls:**
- Designed for keyboard or input. WASD for moving, cursor to aim basic attack, left click to fire
- Hold QER to switch aim to special attacks(QE) or ult(R) and release the button to fire the attack or just tap the button to use it fast without pre-aiming
- Most projectiles will not be able to go through obstacles/walls, with some exceptions

Characters will not be locked to only one per game due to the limited selection of characters. Perhaps this can be implemented in the future.

---

## Future Plans

More characters

More game modes

Expanded maps

Polished progression and balancing
