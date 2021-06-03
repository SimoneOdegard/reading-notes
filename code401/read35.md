# Read 35
[read - Graphs](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/graphs.html)

## WHY

1. GPS and Mapping
1. Driving Directions
1. Social Networks
1. Airline Traffic
1. Netflix uses graphs for suggestions of products

## WHAT

Graph is a non-linear data structure that can be looked at as a collection of vertices/nodes potentially connected by line segments/edges.

### Types of Graphs

- **Undirected Graph** is a graph where each edge is undirected or bi-directional. It does not move in any direction.
- **Directed Graph** is also called a *Digraph*. It is a graph where every edge is directed. Each node is directed at another node with a specific requirement of what node should be referenced next. Arrows point to specific nodes.
- **Complete** is when all nodes are connected to all other nodes.
- **Connected** is when all nodes have at least one edge.
- **Disconnected** is where some nodes may not have edges.
- **Acyclic** is a directed graph without cycles.
- **Cyclic** A graph with cycles.

### Terms

- **Vertex**: Also called a node. A data object that can have 0 or more adjacent vertices
- **Edge**: A connection between two nodes
- **Neighbor**: Adjacent nodes that are connected via an edge
- **Degree**: The number of edges connected to that vertex
- **Cycle**: When a node can be traversed through and potentially end up back at itself

## HOW

**BreadthFirst() traversal method**
1. Enqueue the declared start node into the Queue.
1. Create a loop that will run while the node still has nodes present.
1. Dequeue the first node from the queue
1. if the Dequeue‘d node has unvisited child nodes, add the unvisited children to visited set and insert them into the queue.

**DepthFirst() traversal method**
1. Push the root node into the stack
1. Start a while loop while the stack is not empty
1. Peek at the top node in the stack
1. If the top node has unvisited children, mark the top node as visited, and then Push any unvisited children back into the stack.
1. If the top node does not have any unvisited children, Pop that node off the stack
1. Repeat until the stack is empty

[<== Back](https://simoneodegard.github.io/reading-notes/)