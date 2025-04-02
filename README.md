# Delivery-Route-Optimizer
Delivery Route Optimizer

This is a Python project that implements a Delivery Route Optimizer using Dijkstra's algorithm. The program computes the shortest paths from a given source location to all other delivery locations based on a distance matrix.

Features

Dijkstra's Algorithm: Efficiently calculates the shortest path from the source to every other node.
User Input: Accepts a distance matrix and source index to build a customizable delivery network.
Path Reconstruction: Prints the shortest path along with the distance for each destination.
How It Works

Input:
Enter the number of delivery locations.
Provide the distance matrix where each element represents the distance between two locations.
Specify the source location index.
Processing:
The program uses Dijkstra's algorithm with a priority queue (min-heap) to compute the shortest distances from the source.
It maintains a previous node array to reconstruct the shortest path.
Output:
Displays the shortest path and total distance from the source to every other location
