# Graph-Algorithms-Shortest-Path

This project implements and demonstrates various graph algorithms to find the shortest path between nodes in a graph. 
# The algorithms include:
Dijkstra's Algorithm
A Algorithm*
Bellman-Ford Algorithm
Floyd-Warshall Algorithm
# Features
Visualize the graph using networkx and matplotlib.
Input the graph interactively in Google Colab.
Run and compare the results of different shortest-path algorithms on the graph.
# Algorithms
1. Dijkstra's Algorithm
Dijkstra’s algorithm is a classic shortest-path algorithm. It finds the shortest path from a starting node to all other nodes in a graph with non-negative edge weights.

2. A Algorithm*
A* is a popular graph traversal and shortest-path algorithm that uses heuristics to find the shortest path. It is often used in pathfinding problems like navigation systems and games.

3. Bellman-Ford Algorithm
The Bellman-Ford algorithm computes the shortest paths from a single source node to all other nodes, even when there are negative weight edges. It can also detect negative cycles in the graph.

4. Floyd-Warshall Algorithm
Floyd-Warshall algorithm is used to find the shortest paths between all pairs of nodes in a graph. It works for graphs with negative weights but without negative cycles.

# Requirements
Python 3.x
networkx library
matplotlib library
numpy library
# Installation
You can install the required libraries using pip:

bash
Copy
Edit
pip install networkx matplotlib numpy
# Usage
Step 1: Create and Visualize the Graph
Define the number of nodes and edges in your graph.
Input the edges in the format: node1 node2 weight.
The graph will be visualized using networkx and matplotlib.
Step 2: Run the Algorithms
Once you’ve defined the graph, you can run the following algorithms:

Dijkstra's Algorithm: Finds the shortest path from a starting node to all other nodes.
A Algorithm*: Finds the shortest path to a goal node using a heuristic.
Bellman-Ford Algorithm: Finds the shortest paths from a starting node to all other nodes, and checks for negative cycles.
Floyd-Warshall Algorithm: Computes the shortest paths between all pairs of nodes.
Step 3: Provide Input
Enter the start and goal nodes for the pathfinding algorithms (A*, Dijkstra, Bellman-Ford).
View the output, which will show the shortest path distances and paths (if applicable).
# Example
Input:
bash
Copy
Edit
Enter the number of nodes: 4
Enter the number of edges: 4
Enter edges in format: node1 node2 weight
0 1 10
1 2 5
2 3 2
0 2 15
Output:
Graph Visualization: Shows the nodes and weighted edges.
Algorithm Results:
Shortest path from node 0 to all other nodes using Dijkstra.
Shortest path from node 0 to node 3 using A*.
Shortest path using Bellman-Ford.
All-pairs shortest paths using Floyd-Warshall.
# Notes
This project is designed to run on Google Colab, but it can be easily adapted to run locally.
The algorithms assume an undirected graph unless otherwise specified.
