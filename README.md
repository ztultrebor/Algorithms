# Algorithms

- A collection of algorithms I wrote in conjunction with various online courses
- All code is written in Julia

## Dijkstra's Shortest Path

- Uses a heap to compute the shorest path from a chosen node to all other nodes in an undirected graph by means of Dijkstra's Shortest Path algorithm. 
- You supply the graph (in the correct form of course: Dict{X, Dict{Y, Z}}, where X is a node in the graph, Y is any node adjacent to X and Z is the (positive) distance between them ) and we'll supply the shortest paths.
- The file is thus: DijkstraShortestPath.ipynb

## Binary Search Tree

- A simple binary search tree construction. Use it for whatever you want to use a binary search tree for. Does not contain red.black capability (yet).
- Provides a test case to verify that it works--sort a list of randomized integers. I know that's not what anyone wants a binary search tree for, but it proves that it works properly.
