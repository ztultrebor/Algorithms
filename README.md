# Algorithms

- A collection of algorithms I wrote in conjunction with varius online courses
- All code is written in Julia

## Dijkstra's Shortest Path

- Uses a heap to compute the shorest path from a chosen node to all other nodes in an undirected graph by means of Dijkstra's Shortest Path algorithm. 
- You supply the graph (in the correct form of course: Dict{X, Dict{Y, Z}}, where X is a node in the graph, Y is any node adjacent to X and Z is the (positive) distance between them ) and we'll supply the shortest paths.
- The file is thus: DijkstraShortestPath.ipynb
