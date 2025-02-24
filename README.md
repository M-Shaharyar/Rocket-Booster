# Rocket Booster

## Level 1
![Demo](https://github.com/M-Shaharyar/Rocket-Booster/blob/main/Game%20Gifs/Level%201.gif)

## Level 2
![Demo](https://github.com/M-Shaharyar/Rocket-Booster/blob/main/Game%20Gifs/Level%202.gif)

## Level 3
![Demo](https://github.com/M-Shaharyar/Rocket-Booster/blob/main/Game%20Gifs/Level%203.gif)

## Level 4
![Demo](https://github.com/M-Shaharyar/Rocket-Booster/blob/main/Game%20Gifs/Level%204.gif)

## Overview
Rocket Booster is an exciting Unity-based game where players navigate a rocket from point A to point B while avoiding various obstacles. The game features four levels, with increasing difficulty. The first two levels provide a simple introduction, while the last two levels present a challenging terrain that is difficult to pass.

## How to Play
- Use **Spacebar** (or assigned thrust key) to propel the rocket upwards.
- Use **Left Arrow** for Left Rotation and **Right Arrow** for Right Rotation to steer the rocket.
- Avoid obstacles to prevent crashing.
- Reach the landing platform to complete the level.
- If the rocket crashes into an obstacle, the level restarts.

## Features
- **Physics-Based Movement:** Realistic rocket propulsion and rotation.
- **Level Progression:** Four levels with increasing difficulty.
- **Obstacle Interaction:** Dynamic obstacles requiring precise navigation.
- **Audio & Particle Effects:** Engine sound and thrust visuals enhance immersion.
- **Debug Keys:** `L` key loads the next level, `C` key toggles collision detection.

## Scripts Used

### **CollisionHandler.cs**
- Handles collisions with obstacles and landing platforms.
- Plays crash or success sound effects.
- Loads the next level or restarts the current one.

### **Movement.cs**
- Controls thrust and rotation mechanics.
- Applies physics-based movement to the rocket.
- Manages engine sound and particle effects.

### **Osilator.cs**
- Moves obstacles back and forth using a smooth oscillating motion.
- Enhances level difficulty with dynamic barriers.

### **QuitApplication.cs**
- Allows the player to exit the game using the `Escape` key.

### **LevelMenu.cs**
- Provides a menu to select and load specific levels.

### **MainMenu.cs**
- Controls the main menu functionality.
- Allows players to start the game or quit the application.

## Technologies & Tools Used
- **Game Engine:** Unity
- **Programming Language:** C#
- **Physics Engine:** Unity’s Rigidbody system
- **UI Framework:** Unity UI for menus and level selection

## How to Run the Game
```sh
git clone https://github.com/M-Shaharyar/Rocket-Booster.git
```
- Open the project in Unity.
- Press the **Play** button in the Unity Editor.
- Use the movement controls to navigate the rocket through obstacles.

## Contribution
Contributions are always welcome! Feel free to fork the repository, make improvements, and submit a pull request.

## License
This project is open-source and available under the **MIT License**.
