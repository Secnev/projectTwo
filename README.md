# projectTwo
David Vences

## Objectives
### Problem 1: Single-source Shortest Path Algorithm
Find shortest path tree in both directed and undirected weighted graphs for a given source vertex. Assume there is no negative edge in your graph. You will print each path and path cost for a given source.

### Problem 2: Minimum Spanning Tree Algorithm
Given a connected, undirected, weighted graph, find a spanning tree using edges that minimizes the total weight. Use either Kruskal's or Prim's algorithm to find Minimum Spanning Tree (MST). You will printout edges of the tree and total cost of minimum spanning tree.

### Input Format:

For each problem, you will take input from a text file. Say you want to run algorithm on the following undirected graph.

The corresponding file format would be:

6 10 U
A B 1
A C 2
B C 1
B D 3
B E 2
C D 1
C E 2
D E 4
D F 3
E F 3
A

Here, the first two numbers represent the number of vertices and edges. The letter U stands for undirected graph (D for directed). From the second line, it mentions all edges and its weight (e.g. 
 and its weight is 1. The last line is optional. If given, it represents the source node.

If you prefer different input format, you can do so. But must provide enough details so that TA can run your program easily.

Program Execution:

For each algorithm, run your program for four different graphs of your choice. Use your judgement to define test graphs that you think interesting and reasonable. For example:

Undirected graph: at least 9 nodes and 12 edges
Directed graph: at least 7 nodes and 15 edges

## Instructions
Downloading the project folder and running all cells in the Jupyter Notebook will get the graphs from the txt files included,run the algorithms, and print out the results.
