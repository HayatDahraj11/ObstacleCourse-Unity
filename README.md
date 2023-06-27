#  First Unity Game - 3D Movement and Physics

## Description

This repository contains my first Unity 3D game project where I explored the fundamentals of Unity game development. This includes the basics of game physics, object movement, timers, and camera setups using Cinemachine. The game is a simple platformer where the player navigates through a 3D environment, with objects falling from above that the player must avoid.

## What I Learned

Throughout the development of this project, I grasped the following concepts:

1.  **Basic Object Manipulation**: Understood how to manipulate game objects' transformations for movement within the game world.
2.  **Physics and Collisions**: Learned how to use Unity's physics engine to create more realistic movement and to implement collision detection between game objects using Unity's `OnCollisionEnter()` method.
3.  **Timers and Time Management**: Learned how Unity handles time and how to create timers in Unity using `Time.deltaTime` and `Time.time`. Understood how to use these to control game events like delaying the fall of objects.
4.  **Component Referencing**: Understood the importance of caching references to often-used components for performance enhancement, and learned how to access various components using Unity's `GetComponent<>()` method.
5.  **Use of SerializeField**: Learned how to use `SerializeField` to expose private variables in Unity's inspector, enabling easy tweaking of game parameters without hard-coding.
6.  **Working with Rigidbodies**: Learned the usage of Unity's `Rigidbody` component to incorporate realistic physics into game objects, including gravity and collision responses.
7.  **Camera Management with Cinemachine**: Learned how to setup and manage the game camera using Cinemachine, which allowed for more complex and dynamic camera movements with less effort.

## Scripts Description

1.  `Mover.cs`: This script handles player movement. It includes instructions for the player and maps keyboard inputs to player movement in the game world.
2.  `ObjectHit.cs`: This script changes the color of the game object (to yellow) when it is hit by the player. It also changes the object's tag to "Hit" upon collision.
3.  `Dropper.cs`: This script is attached to game objects that are supposed to fall from above after a certain amount of time. It starts with the objects invisible and not influenced by gravity, which are then activated after a specified wait time.
4.  `Scorer.cs`: This script keeps track of how many times the player has collided with objects that aren't tagged as "Hit". It outputs the score to the console.

## Future Improvements

In the future, I plan to expand on this project by adding more complex mechanics, more levels, and better visuals. This first game has provided me with a solid foundation in Unity game development, which I will continue to build upon.

## Usage

To try the game yourself, download the repository and open the project in Unity. Navigate to the scene you wish to play and click the play button in Unity. Use the WASD or arrow keys to move your player in the game world.


https://github.com/HayatDahraj11/ObstacleCourse-Unity/assets/99029950/aa806c1c-d948-419a-afa6-becb6a2fc69c


