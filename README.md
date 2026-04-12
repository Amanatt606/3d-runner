#  3D Runner Game

##  Project Description
This project is a 3D endless runner game developed in Unity. The player automatically moves forward while avoiding obstacles and collecting points. The main goal is to survive as long as possible and achieve the highest score.
<img width="1574" height="908" alt="image" src="https://github.com/user-attachments/assets/c76ff446-685f-462c-b094-4b40ed28e115" />



##  Core Movement System
The player character moves forward automatically at a constant speed. The player can move left and right to avoid obstacles. The character also has a jump ability, allowing it to overcome obstacles on the path.



##  Camera System
The game includes a third-person follow camera that tracks the player from behind. A second camera is also implemented to provide an alternative view of the gameplay. The player can switch between the two camera perspectives during gameplay.



##  Gameplay Features
- Automatic forward movement  
- Left and right movement  
- Jump mechanic  
- Obstacles that cause game over on collision  
- Score system based on survival/collection  
- Restart system after losing  
<img width="1502" height="895" alt="image" src="https://github.com/user-attachments/assets/85232674-3e75-404f-8d65-bbcc6cba5d18" />



##  Gameplay Loop
The game follows a complete gameplay loop:
Start → Playing → Lose → Restart

- The game starts in a ready state  
- The player plays by avoiding obstacles  
- Collision with an obstacle triggers the lose state  
- The player can restart the game using a restart button  



##  UI and Feedback
The UI displays the player’s score during gameplay. A game over panel appears when the player loses, along with a restart button. These elements provide clear feedback to the player.

---

##  Technical Implementation
The project uses Unity physics with colliders and triggers for obstacle detection and scoring. Scripts are properly attached to game objects, and the project runs without errors in the console. The hierarchy is organized and readable.

---

##  Conclusion
The project successfully implements a functional 3D runner game with movement, obstacles, scoring, camera switching, and a complete gameplay loop.
