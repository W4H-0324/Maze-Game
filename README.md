# Maze-Game

# Features:
1.	Randomly Generated Maze: Maze dimensions the maze has a fixed size of 100x100 cells. Boundary walls the maze has solid boundaries (#) on all four sides. Random obstacles 20% of the maze cells are randomly filled with obstacles (#). Empty spaces Remaining cells are empty ( ). Player and exit placement The player (P) starts at the top-left corner, and the exit (E) is placed at the bottom-right corner.

2.	Limited Vision: Vision range The player can see a 10x10 area around their current position. Vision boundaries Outside the vision range, the maze is hidden by boundary symbols (#). Real-time updates The vision updates dynamically as the player moves.


3.	Player Movement: Movement keys W (up), A (left), S (down), and D (right) keys control player movement. Cell-based movement the player moves one cell at a time. 
Collision detection the player cannot move through obstacles (#) or boundaries.


4.	Time Tracking: Start time the timer starts when the game begins. Real-time display the current time is displayed below the maze. Time unit time is measured in seconds.


5.	Win Condition: Exit location the exit (E) is located at the bottom-right corner. Win criteria the player wins by reaching the exit. Game termination the game ends upon winning.


6.	Score Saving: File name the completion time is saved to "Time.txt". Append mode new scores are appended to the existing file. Score format: scores are displayed in seconds (e.g., "Time: 120 seconds"). Error handling errors opening the file are displayed on the console.


   # Data Structures:
   1.	2D array (Maze Structure):
•	Usage: Represent the game maze, storing characters for boundaries, path/empty space, obstacle and special entities(P for player, E for exit).
•	Operation:	Maze: O(n), initialize the game maze by setting up its structure, boundaries, obstacle and players/exits positions.

2.	Heap (Dynamic memory allocation for the file stream):
•	Usage: It records the player completion time. 
•	Operation:	Save Time Record: It saves the players time completion in a located txt file.

3.	Stack / Variables (Stack base allocation for variables):
•	Usage: Setting the players and exit location inside the maze.
•	Operation:	Handle Input: O(1) - it Purpose to Store player.



