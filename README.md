# Whack-A-Mole: A Classic Arcade Game Reimagined for iOS
<img src="https://github.com/devpsoni/Whack-A-Mole/assets/43056706/45a91059-a3a8-4fb5-beb5-3d5857904dc4" alt="drawing" width="200"/>
<img src="https://github.com/devpsoni/Whack-A-Mole/assets/43056706/90556b83-4e0e-478d-9157-ca07ccbafe39" alt="drawing" width="200"/>
<img src="https://github.com/devpsoni/Whack-A-Mole/assets/43056706/bcca588e-a8c6-4baa-8011-af8ae8b4ad9e" alt="drawing" width="200"/>

## Features:
- **Classic Gameplay**: Tap to whack the moles as they pop out of their holes but beware of the bombs!
- **Score Tracking**: Keep an eye on your score with a live-updating label.
- **Countdown Timer**: Race against the clock, with a timer that adds to the challenge.
- **High Score System**: Achieve a high score and enter your name to immortalize your place on the leaderboard.

## Getting Started:
Just hit the "Start!" button and prepare to test your reflexes. Moles will appear at random, and it's your job to whack them back into their holes. But, stay alert! Some moles come with a surprise – bombs that can end your game prematurely.

## Game Mechanics:
- **Random Appearance**: Moles show up in random holes at varying intervals, ensuring each game is unique.
- **Interactive Holes**: Each hole is tap-recognizable, making for smooth and responsive gameplay.
- **Bombs**: Adds an element of unpredictability and increases the game's difficulty.

## Scoring and Timekeeping:
- **Dynamic Score Update**: Your score is updated with each successful whack.
- **Timer Countdown**: A 59-second countdown timer keeps the pressure on.
- **End-of-Game Alerts**: When the time's up, you'll know if it's time to celebrate a new high score or simply try again.

## High Score Registration:
Set a new high score and you'll be prompted to enter your name, immortalizing your achievement in the game's hall of fame.

## Behind the Scenes:
- **Timer-Driven Logic**: Timers control the appearance of moles and the game's countdown.
- **User Defaults**: High scores and player names are saved using UserDefaults for persistence.

## Code Architecture:
- **View Controllers**: `GameViewController` for the gameplay logic and `ViewController` for the start screen.
- **UIKit**: The use of UIKit for UI elements such as UIImageViews for holes and UILabels for score and timer.

## User Interface:
- **Attractive Graphics**: A playful and colorful interface that's easy on the eyes.
- **Simple Navigation**: Easy-to-navigate screens with clear labels for scores and timing.
