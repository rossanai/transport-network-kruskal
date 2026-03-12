# Transport Network Optimization using Kruskal's Algorithm

This project models a transportation network and computes the most fuel-efficient routes between stops.

The transportation system is represented as a weighted graph where:

- vertices represent transportation stops
- edges represent routes between stops
- weights represent diesel fuel consumption

To minimize the total fuel consumption, the program computes a Minimum Spanning Tree (MST) using Kruskal's algorithm.

## Main Components

### Route
Represents a connection between two stops and the fuel cost between them.

### Graph
Stores all routes and implements Kruskal's algorithm to find the optimal connections.

### Union-Find
The method encontrar is used to determine the representative of a set to detect cycles when building the MST.

### File Loading
The function cargarGrafoDesdeArchivo reads the transportation network from a file and loads it into the graph.

## Concepts Demonstrated

- Graph data structures
- Kruskal's algorithm
- Minimum Spanning Tree
- Union-Find / Disjoint Sets
- File input processing
