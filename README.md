# Dijkstra's Algorithm on a Weighted Graph

## Description

This project uses **NetworkX** to generate and visualize a random weighted graph. It also implements Dijkstra’s algorithm to find the shortest paths from a user-specified starting vertex.

## Requirements

You’ll need these libraries to run the code:

- **networkx**: to create and manipulate graphs.
- **numpy**: to generate random numbers, including the edge weights.
- **matplotlib**: to plot the graph visually.
- **heapq**: used for the priority queue in Dijkstra’s algorithm.

## Features
- Random Weighted Graph Generation:
    - A random graph is generated using NetworkX’s gnm_random_graph function, which creates an undirected graph with 10 vertices and 35 edges. Edge weights are randomly assigned using numpy's randint function, ranging from 1 to 15.

- Graph Visualization:
    - The generated graph is displayed in a circular layout, with nodes labeled and edge weights shown.

- Dijkstra’s Algorithm:
    - The user picks a starting vertex (between 0 and 9), and Dijkstra’s algorithm finds the shortest paths from that vertex to every other vertex in the graph.

- Shortest Paths Visualization:
    - The graph is redrawn, highlighting the shortest paths found in red. Nodes are labeled with their indices and distances from the starting vertex (example "5 (8)": node '5' and distance = 8).


## Authors
- Lucas Fiuza Garcia - [GitHub](https://github.com/LuEx10)
- Luis Felipe Marrote Ferreira - [GitHub](https://github.com/LuisFelipeMarrote)
- Thiago Loureiro Kosciuk - [GitHub](https://github.com/ThiagoKosciuk)

This project was developed for studying and practicing graph algorithms and shortest path finding.
