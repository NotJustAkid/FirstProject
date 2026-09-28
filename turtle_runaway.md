# Cat Vs Mouse

* How this game works:
    * 🐭 Mouse (runner) = RandomMover, controlled by AI
    * 🐱 Cat (chaser) = ManualMover, controlled with arrow keys
    * 🍕 Pizza spawns every 3 seconds
    * 🌟 Both players get points for collecting Pizza
    * 🕓 30-second countdown
    * The higher score wins 🏆
    
*Adjustment to the code:
    *Added a cheese spawning system that creates cheese randomly every 3 seconds.
    *Added a scoring system for both the mouse and cat when they collect cheese.
    *Added a 30-second countdown timer for the game.
    *Added a winner system that compares the mouse and cat scores.
    *Added cat and mouse animations by switching between two images when they move (when moving and not moving).
    *Added separate displays for the timer, score, and winner message.
    *Added a game-over system that stops the game when the timer ends.