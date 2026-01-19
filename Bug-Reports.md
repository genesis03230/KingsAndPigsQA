# Bug Reports – Kings and Pigs

---

## BUG-01: Level Can Be Completed With Partial Item Collection

### Environment
- Engine: Unity 6 (2D URP)
- Platform: PC
- Build: Prototype (Playable Core Mechanics)

### Severity
Medium

### Priority
Medium

### Description
During gameplay, the player is able to complete the level and transition to the next scene even if not all required collectible items have been collected.  
This behavior breaks the intended progression rules and reduces the challenge and consistency of the gameplay experience.

### Steps to Reproduce
1. Start a playable level
2. Collect only part of the required items
3. Navigate the player character to the level exit
4. Interact with the exit

### Expected Result
- The level exit should remain locked or inactive
- The player should be required to collect all mandatory items before completing the level

### Actual Result
- The level can be completed despite partial item collection
- The game transitions to the next scene

### Impact
- Breaks level progression rules
- Reduces gameplay challenge
- Allows unintended level completion

### Evidence
- 🎥 Video (Full reproduction): [
KingsAndPigs-BUG-01-PartialItemCollectionAllowsCompletion](https://www.youtube.com/watch?v=jjT-xe8j3bc)
- 🖼️ Visual preview (GIF): available in the `Evidence` folder

