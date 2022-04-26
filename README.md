# IS-211-Assignment-3

A. Network management

This code implements Dijkstra’s algorithm to find the shortest paths between two locations. I chose to build up the structure with six classes, four of which was added to naturally structure the scenario, these being Edge, Vertex, Graph and QueueObject. The last two classes are Main, for running the scenario, and Dijkstra, which contains the algorithm. Dijkstra is a brute force algorithm, which secures that the cheapest way from a start to end.
The rest of the classes can be explained as this. Edge represents the weight between Vertices while Vertex represents the node, or the location in the scenario. Graph contains the vertices and QueueObject is for ordering the objects based on the natural order.

Outputs from the code:

Shortest distance on path from A to B:
10
Entire path:
A
B

Shortest distance on path from A to C:
5
Entire path:
A
C

Shortest distance on path from A to D:
15
Entire path:
A
E
D

Shortest distance on path from A to E:
3
Entire path:
A
E

Shortest distance on path from A to F:
12
Entire path:
A
F

Shortest distance on path from B to C:
15
Entire path:
B
A
C

Shortest distance on path from B to D:
9
Entire path:
B
D

Shortest distance on path from B to E:
13
Entire path:
B
A
E

Shortest distance on path from B to F:
12
Entire path:
B
F

Shortest distance on path from C to D:
15
Entire path:
C
E
D

Shortest distance on path from C to E:
3
Entire path:
C
E

Shortest distance on path from C to F:
12
Entire path:
C
F

Shortest distance on path from D to E:
12
Entire path:
D
E

Shortest distance on path from D to F:
21
Entire path:
D
B
F

Shortest distance on path from E to F:
12
Entire path:
E
F
