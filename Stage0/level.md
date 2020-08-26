# Levels

## Lets user choose the level or speed of the ball in balls per minute

1. 30 rpm
2. 60 rpm
3. 120 rpm
4. Random Speed

## Acceptance Criteria

### Scenario: User wants to set the level of the game

  Given the user has entered the game.

  When the user chooses Select Level button.

  Then show the 4 options and set ball speed to 30, 60, 120
  rotations per minute if level selected is 1, 2, 3 respectively.
  If level 4 is selected then show pop up box asking
  user to enter rotations per minute. Set rotations as
  per the user entry.
