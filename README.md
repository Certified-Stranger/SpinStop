# SPINSTOP
Test your reflexes and precision by stopping a rotating dial hand directly inside a highlighted target zone on a circular lock, choosing between three distinct game modes to achieve high scores or crack sequential levels.

Player Controls
Desktop: Press the Spacebar or Left-Click anywhere on the game screen to lock in your timing.

Mobile / Tablet: Tap anywhere on the screen.(Single-button control makes the game accessible and responsive on any device.)

Gameplay
The player selects one of three game modes from the start menu: Endless, 3-Lives, or Lockpicker.

A circular dial appears with a rotating pointer hand and a colored target arc positioned somewhere along the ring.

When the pointer passes over the target arc, the player presses the input button to hit the target.

Upon a successful hit, the target arc relocates to a new random position on the circle, and the pointer either reverses direction or increases its rotation speed.

Scoring
Endless Mode: Each successful hit awards +1 point and incrementally increases pointer speed. Best scores are saved automatically in the browser using localStorage.

3-Lives Mode: Standard hits award +10 points, while hitting the exact center "sweet spot" of the arc awards a +25 point precision bonus and builds a combo multiplier.

Lockpicker Mode: Tracks levels completed (e.g., Level 1 requires 10 consecutive hits, Level 2 requires 15, scaling upward) along with the player's highest unlocked level.

Win/Lose Rules
Endless Mode: There is no final "win" state; the goal is to survive as long as possible. The player loses immediately upon clicking outside the target zone or letting the pointer pass completely past the target without clicking.

3-Lives Mode: The player starts with 3 hearts and loses when all 3 hearts are depleted from missed clicks or passed targets.

Lockpicker Mode: The player wins a level by reaching the required streak of consecutive hits without a mistake. A single miss resets the current level's progress to zero.
