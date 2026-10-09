# Sukuna Finger Catching Game

## Overview

Sukuna Finger Catching Game is an interactive game I developed using Scratch 3.0 while learning the fundamentals of programming through Harvard's CS50 Introduction to Programming with Scratch course.

Inspired by the anime *Jujutsu Kaisen*, the game features Sukuna as the main character. Players control Sukuna to collect falling fingers while trying to avoid missing them. The game includes a collection system, missed-object tracking, and separate victory and game-over screens.

I created this project to apply programming concepts such as loops, conditions, variables, events, and custom blocks in a practical and interactive way. It also gave me experience designing game mechanics, debugging scripts, and coordinating interactions between different sprites.

## Technologies Used

- **Scratch 3.0:** Visual programming environment used to develop the game.
- **Block-Based Programming:** Used to implement character movement, object interactions, and game logic.
- **Event-Driven Programming:** Used to coordinate gameplay through events and broadcast messages.

## Key Features

- **Character Movement:** Players control Sukuna to collect falling fingers.
- **Collectible Objects:** Fingers appear during gameplay and can be collected by the player.
- **Progress Tracking:** Variables track the number of fingers collected and missed.
- **Victory Condition:** The game displays a victory screen when the required collection goal is achieved.
- **Game-Over Condition:** Missing three fingers ends the game.
- **Multiple Backdrops:** Different backdrops are used for gameplay, victory, and game over.
- **Broadcast Messages:** Coordinate transitions between different game states.
- **Cloning:** Allows game objects to be created dynamically during gameplay.
- **Custom Blocks:** Organize instructions into reusable sections.

## Gameplay Screenshots

### Main Gameplay

The main gameplay screen shows Sukuna collecting falling fingers.

![Sukuna Finger Catching Game - Main Gameplay](screenshots/gameplay.png)

### Victory Screen

The victory screen appears when the player successfully completes the collection objective.

![Sukuna Finger Catching Game - Victory Screen](screenshots/victory.png)

### Game-Over Screen

The game-over screen appears when the player misses three fingers.

![Sukuna Finger Catching Game - Game Over Screen](screenshots/game-over.png)

## How to Play

1. Open the project in Scratch.
2. Click the green flag to start the game.
3. Control Sukuna to collect the falling fingers.
4. Collect the required number of fingers to win.
5. Avoid missing three fingers, as this triggers the game-over screen.
6. Click the green flag to restart the game.

## Programming Concepts Used

### 1. Events and Broadcast Messages

The game uses Scratch events to start gameplay and broadcast messages to communicate between sprites.

These messages help coordinate transitions between the gameplay, victory, and game-over screens.

### 2. Variables

Variables are used to track the player's progress, including the number of fingers collected and missed.

They also help determine when the game should end.

### 3. Loops

Loops allow instructions to run repeatedly during gameplay, supporting continuous game behavior and object interactions.

### 4. Conditional Statements

Conditional statements are used to check whether fingers have been collected or missed and determine whether the player has won or lost.

### 5. Cloning

Cloning allows additional instances of game objects to appear without creating separate sprites manually.

### 6. Custom Blocks

Custom blocks organize related instructions into reusable sections, making the project easier to understand and modify.

## How to Run the Project

### Option 1: Open the Scratch Project File

1. Download `Sukuna-Finger-Catching-Game.sb3` from this repository.
2. Visit [Scratch Editor](https://scratch.mit.edu/projects/editor/).
3. Click **File → Load from your computer**.
4. Select the downloaded `.sb3` file.
5. Click the green flag to start the game.

No additional software or libraries are required.

### Option 2: Play on Scratch

If the project is published on Scratch, it can also be played directly in a web browser.

*A direct Scratch project link can be added here after publication.*

## Development Process

I began by designing the basic gameplay concept and deciding how the player would interact with falling objects.

I then created the character movement and finger-collection mechanics. After implementing these features, I introduced variables to track progress and added conditions to determine when the player should win or lose.

One of the main challenges was coordinating Sukuna's visibility with the different game screens. During development, I encountered an issue where the character did not disappear correctly after the game ended and later did not reappear when restarting.

I worked through these problems by reviewing the scripts, checking the relevant events, and adjusting how the character responded to changes in the game state.

Testing and debugging these interactions helped me better understand how different Scratch scripts work together.

## What I Learned

Developing this game strengthened my understanding of fundamental programming concepts and how they can be applied to interactive projects.

Through this project, I learned how to:

- Use variables to store and update game information.
- Apply loops and conditional statements to control gameplay.
- Use events and broadcasts to coordinate multiple sprites.
- Work with clones and custom blocks.
- Implement victory and game-over conditions.
- Debug problems involving sprite visibility and game-state transitions.

This project also helped me develop patience and problem-solving skills, particularly when identifying why certain scripts were not behaving as expected.

## Disclaimer

This is a fan-made educational project inspired by *Jujutsu Kaisen*. It was created for programming practice and is not affiliated with or endorsed by the creators or rights holders of the series.

## Author

**Veer Sinha**

Developed as part of my programming practice while studying Harvard's CS50 Introduction to Programming with Scratch.
