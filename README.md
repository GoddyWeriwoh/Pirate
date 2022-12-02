APDS Project: Pirates of the Mediterranean

This project has been developed using Java as programming language. Regarding the IDE, we used IntelliJ IDEA to develop the code in Java.

To execute the code, the "Code" folder includes the project  that has to be opened with IntelliJ IDEA. 
After opening the project, the Main.java file inside the src folder has to be opened. 
Once in Main.java, the public void  main method has to be exectued, after that the code will run.

One of the most important points in piratical planning consisted in finding optimal routes between
points of interest (treasure troves, black markets...) while avoiding certain obstacles (highly guarded
ports, sea monster lairs...).

GRAPH:
About how we implemented the graph in our project, we decided to use an adjacency list. This
implementation consists on a graph having a list of vertexes, and each vertex has a list containing
all the adjacent vertex with which it makes an edge.

DFS(Depth First Search) Algorithm:
To be able to run this algorithm, at the beginning all nodes need to be marked as not visited
and through the process of going through all the nodes they need to be marked as visited.

 BFS(Breadth First Search) Algorithm:
Similar to DFS but BFS does not use recursion to go
through its nodes and the other difference is that BFS consists on visiting all the adjacent nodes
of a node before looking to more adjacent nodes.
 
MST Algorithm:
Regarding our implementation, we followed
the Kruskal implementation. It consists on starting with a graph with all the nodes disconnected
and it connects them choosing the edges with the less weight from the original graph and
checking if the built graph is already a MST or not

Dijkstra Shortest Path Algorithm
This algorithm consists on finding the shortest path between two nodes from a weighted graph.
The algorithm starts from a node and then it stores the walk to reach each node and the weight
of those walks then with certain steps the algorithm updates the walks and the weights of the
walks until it finds the shortest path.

 
