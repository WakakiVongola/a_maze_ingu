# A-MAZE-ingu

## Requirements

- Main Menu:
  - Start button
  - Level selector menu
  - Settings/Parameters button
  - Quit button
- Pause Menu
- Gameplay HUD:
  - Timer
  - Number of lives
- Gameplay Features:
  - Traps and jump areas
  - In-game sound controller
- Animations:
  - "I’ve played this game before!" voiceline animation
  - Fall trap animation (with Wilhelm scream)
  - Win dance animation
- Music:
  - Coucou les Congolais
  - Valhalla (Assassin's Creed)

---

## Game Scenario

### Start Menu
- The game begins on the main menu.
- When the user clicks on the "Start" button,  
  Then the game starts, and the map and character are displayed.

### Character Introduction
- Then the character says his voiceline:  
  "I’ve played this game before!"  
- Then the player can move the character in the following directions:  
  Left (L), Right (R), Forward (F), Backward (B).

### Wall Collision
- When the character moves into a wall,  
  Then the character collides and cannot pass through.

### Traps
- When the character steps on a trap:  
  - Then the ground on the trap disappears.  
    - (Clarification needed: Should all ground around disappear, or only specific ground?)  
- When the player falls into the trap:  
  - Then the Wilhelm scream is triggered.  
  - Then the player loses one life.  
  - Then the game restarts.

### Game Over
- When the player loses all 3 lives:  
  - Then the game is over.  
  - Then a "Game Over" message is displayed.  
  - Then the player is returned to the main menu.

### Win Condition
- When the player reaches the end of the maze:  
  - Then the character performs a win dance.  
  - Then the game closes.
