# Graph-Coloring-Methods 
Given an undirected graph G = [N, E], two methods will be used to find the minimum number of colors to color all nodes in N such that no 2 adjacent nodes Ni & Nj can be colored with the same color.

Input#1 (argv[1]): an undirected graph represented by a list of edges [Ni, Nj], which is a bidirectional edge from Ni to Nj and from Nj to Ni with cost of C. The first number is the number of nodes N in graph G, follows by a list of bidirectional edges [Ni, Nj].

Output#1 (argv[2]): Prints

1. input pairs
2. initial adjacencyMatrix of graph
3. number of colors used to color
4. the final adjacencyMatrix with the assign colors in the diagonal of the matrix

-------------------------------------------------------------------------------------------------------------------------------------------

Method#1:
Take one color and color all possible nodes, then add a new color when run out of choices. Repeat until all nodes are colored.

Method#2:
Color each node with existing "used colors" if possible, else add a new color. Repeat until all nodes are colored.
