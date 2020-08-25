# Main Menu

## Feature

Main Menu

- Play Game
- Select Level
- Quit Game

## Acceptance Criteria

### Scenario: Play Game is selected

  Given the player wants to play the last played level.

  When Play Game is selected.

  Then Google Play Account Sign-In option appears
  and game resumes with a counter counting 3, 2
  and 1 before launching the game.

### Scenario: Select Level is selected

  Given the player wants to play another level.
  
  When Select Level is selected.
  
  Then ask the user to choose the level to play
  and resume the game with counter before launching
  the game.
  
### Scenario: Quit Game is selected

  Given the player wants to quit the game.
  
  When Quit Game is selected.
  
  Then save the game state and close the game.
