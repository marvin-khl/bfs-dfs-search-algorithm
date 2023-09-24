# bfs-dfs-search-algorithm
Python script that utilizes breadth-first search (BFS) and depth-first search (DFS) algorithms to explore connections between actors and actresses in the context of movies. This project is an assignment from the first lecture of Harvard's CS50 Course, focusing on AI and Python programming.

# Six Degrees of Kevin Bacon Game Solver
Overview:

The Six Degrees of Kevin Bacon game is a fun and intriguing concept in the Hollywood film industry. It posits that any actor or actress in Hollywood can be connected to the legendary actor Kevin Bacon within six steps or fewer. Each step in this game represents finding a film where two actors have starred together.

This project is designed to solve the challenge of finding the shortest path between any two actors or actresses by identifying a sequence of movies that connects them. For example, if you want to determine the shortest path between Jennifer Lawrence and Tom Hanks, this solver can find it for you. In this case, the shortest path would be 2 steps: Jennifer Lawrence connects to Kevin Bacon through a common movie, and Kevin Bacon connects to Tom Hanks in another.

# Search Problem:

This project frames the challenge as a search problem. The states in this problem represent people (actors and actresses), while the actions represent movies. Each action (movie) takes us from one actor to another, potentially leading to multiple different actors in the next step. The initial state and the goal state are defined by the two individuals we're attempting to connect.

# Breadth-First Search (BFS):

To solve this problem efficiently, the project utilizes the breadth-first search (BFS) algorithm. BFS systematically explores different paths from the initial actor to the goal actor by analyzing movies and their connections. It calculates the shortest path by minimizing the number of steps (movies) required to connect the two individuals.

# Usage:

Users can provide the names of two actors or actresses as input.
The solver then uses BFS to find the shortest path between them, displaying the degrees of separation and the movies that connect them.
This project is not only a practical tool for exploring Hollywood connections but also a fascinating example of how search algorithms can be applied to real-world problems. Enjoy playing the Six Degrees of Kevin Bacon game with a computational twist!

https://cs50.harvard.edu/ai/2023/projects/0/degrees/
