# Kings and Pigs – QA Manual Testing

## Project Overview
Kings and Pigs is a 2D pixel art platformer developed in Unity, focused on responsive controls, level design, and progressive gameplay mechanics.

- Engine: Unity 6 (2D URP)
- Platform: PC
- Game Type: 2D Platformer
- Status: Prototype (Playable Core Mechanics)

This project is currently under development and is being expanded from a learning prototype into a complete indie game.

## Core Objective
The player must navigate platforming levels, avoid hazards, defeat enemies, collect required items, and reach the level exit according to defined progression rules.

## QA Scope
The QA activities for this project focus on:
- Level progression and completion rules
- Collectible validation and tracking
- Player interaction with exits and transitions
- Gameplay consistency in prototype environments
- Prevention of unintended level completion

## Known Risk Areas
- Partial collection of required items
- Exit and door validation logic
- Scene transitions without proper completion checks
- Prototype mechanics lacking final constraints

## Visual QA Preview

The following preview demonstrates a progression issue identified during manual testing.  
In this scenario, the player is able to complete the level and transition to the next scene despite collecting only part of the required items.

![KingsAndPigs-BUG-01-PartialItemCollectionAllowsCompletion](https://github.com/user-attachments/assets/c4e0ebff-fc95-44e4-a4f1-536e3dcacc5c)

> Full reproduction steps, severity, and complete video evidence are documented in `Bug-Reports.md`.

## Test Artifacts
- 📄 [Manual Test Cases](Test-Cases.md)
- 🐞 [Bug Reports with Evidence](Bug-Reports.md)

