# Cat Vs Mouse

* How this game works:
    * 🐭 Mouse (runner) = RandomMover, controlled by AI
    * 🐱 Cat (chaser) = ManualMover, controlled with arrow keys
    * 🍕 Pizza spawns every 3 seconds
    * 🌟 Both players get points for collecting Pizza
    * 🕓 30-second countdown
    * The higher score wins 🏆
    
* Adjustment to the code:
    * Pizza spawning system that creates cheese randomly every 3 seconds.
    * Scoring system for both the mouse and cat when they collect pizza.
    * 30-second countdown timer for the game.
    * Winner system that compares the mouse and cat scores.
    * Cat and mouse animations by switching between two images when they move (when moving and not moving).
    * Separate displays for the timer, score, and winner message.
    * Game-over system that stops the game when the timer ends.