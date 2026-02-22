DijkstraFlow – Task Optimization Tool

DijkstraFlow is a web-based task scheduling and optimization tool that models task dependencies using graph theory and applies Dijkstra’s Algorithm to determine an optimized execution order based on priority weights.
The application allows users to define tasks, assign priorities, and specify dependencies. It then constructs a directed graph and computes an optimized task sequence while visually representing task relationships using an interactive network graph.

 Features
-> Add tasks with priority levels
-> Define task dependencies (Directed Graph structure)
-> Optimize task order using Dijkstra’s Algorithm
-> Interactive dependency visualization using vis-network
-> Clean, responsive UI with hierarchical graph layout
-> Real-time task list updates

 Tech Stack
HTML5 – Structure
CSS3 – Styling and responsive layout
JavaScript (Vanilla JS) – Logic and algorithm implementation
Dijkstra’s Algorithm – Optimization logic
vis-network.js – Graph visualization

 How It Works
->Each task is treated as a node in a directed graph.
->Dependencies create edges between nodes.
->Task priority is used as the edge weight.
->A virtual _start_ node connects tasks without dependencies.
->Dijkstra’s Algorithm calculates the shortest weighted path.
->Tasks are ordered based on computed distances for optimized execution.

 Use Case
->Academic demonstration of graph algorithms
->Understanding dependency-based scheduling
->Visual learning of shortest path algorithms
->Mini-project for Data Structures & Algorithms

 Future Enhancements
->Implement Topological Sorting for true DAG scheduling
->Add task editing and deletion
->Export task list to JSON/CSV
->Persistent storage using LocalStorage
->Performance optimization for large datasets
