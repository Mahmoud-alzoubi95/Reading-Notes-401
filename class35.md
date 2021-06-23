# Graphs

A graph is a non-linear data structure that can be looked at as a collection of `vertices` (or `nodes`) potentially connected by line segments named `edges`.

Here is some common terminology used when working with Graphs:

1. *Vertex* -  A vertex, also called a "node", is a data object that can have zero or more adjacent vertices.
1. *Edge* - An edge is a connection between two nodes.
1. *Neighbor* - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
1. *Degree* - The degree of a vertex is the number of edges connected to that vertex.

## Directed vs Undirected

### Undirected Graphs

An `Undirected Graph` is a graph where each edge is undirected or bi-directional. This means that the undirected graph does not move in any direction.

For example, in the graph below, Node `C` is connected to `Node A`, `Node E` and `Node B`.
There are no "directions" given to point to specific vertices. The connection is bi-directional.

![](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/UndirectedGraph.PNG)

The undirected graph we are looking at has 6 vertices and 7 undirected edges.

Vertices/Nodes = {a,b,c,d,e,f}

Edges = {(a,c),(a,d),(b,c),(b,f),(c,e),(d,e),(e,f)}


## Complete vs Connected vs Disconnected
There are many different types of graphs. This depends on how connected the graphs are to other node/vertices.
The three different types are completed, connected, and disconnected.

## Acyclic vs Cyclic
In addition to undirected and directed graphs, we also have acyclic and cyclic graphs.



## Real World Uses of Graphs
Graphs are extremely popular when it comes to it's uses. Here are just
a few examples of graphs in use:

1. GPS and Mapping
1. Driving Directions
1. Social Networks
1. Airline Traffic
1. Netflix uses graphs for suggestions of products

There is a lot to graphs, and a lot you can do with them. Let this be document be used as an introduction to graphs. There is a lot more to them then described, so start exploring, and have fun with them!
