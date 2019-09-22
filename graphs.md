UNDIRECTED 
1. adjMatrix
2. DFS 
3. BFS
4.
.
.
. Cycles in UNDIRECTED GRAPH (idea: visited marking is imp 1->2->1 where did you come from (cameFromVertex, visited) 
DFS(1, 0) -> DFS(2,1) -> DFS(3, 2) -> DFS (4, 3)  
=
if any of the vertices other than the one you came from is already visited => there exists a cycle in this particular connected component of the undirected graph....MAYBE
