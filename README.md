# Snake

The provided code implements a simple Snake and Ladder game using a breadth-first search (BFS) algorithm to find the minimum number of moves required for a player to reach the destination (position 100) on the game board. The game board contains ladders and snakes, which can move the player to different positions on the board. The code uses an unordered map to represent the ladder and snake positions, and a queue to perform BFS traversal. The project demonstrates basic algorithmic problem-solving skills and data structure usage.

Usage of Data Structures and Algorithms:
In this project, you have utilized the following data structures and algorithms:

Unordered Map: The unordered map is used to store the positions of ladders and snakes on the game board. It provides efficient lookup (constant time complexity on average) to determine if the current position has a ladder or snake.

Queue (BFS): The queue is used to perform Breadth-First Search (BFS) traversal on the game board. It helps to explore all possible moves from the current position and find the shortest path to reach the destination (position 100). BFS guarantees the shortest path in unweighted graphs like this game board.
