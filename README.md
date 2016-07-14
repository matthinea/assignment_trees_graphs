a sequoia by Matt and Graham

# assignment_graphs_trees
Rise over run.

[A Data Structures and Algorithms Ruby Assignment from the Viking Code School using Trees and Graphs](http://www.vikingcodeschool.com)


    What are the advantages and disadvantages of using an Adjacency Matrix vs an Adjacency List relative to size and speed of common operations?
      Adjacency matrices have larger memory footprints but random access is much quicker. 
      Adjacency list has a smaller footprint and relatively quickly random access, if it's balanced. For a balanced hash list, random access is O(1).


    What would the Big O be of inserting a new EDGE to:
        An Edge List? O(n)
        An Adjacency Matrix? O(1
        An Adjacency List? O(n)
    What would the Big O be of inserting a new VERTEX to:
        An Edge List? O(n)
        An Adjacency Matrix? O(n)
        An Adjacency List? O(1)
    What would the Big O be of REMOVING a vertex or edge from:
        An Edge List? O(n)
        An Adjacency Matrix? O(n)
        An Adjacency List? O(1)
    How would you find all the nodes connected to a particular vertex in:
        An Edge List? iterate through the list, when a vertex is found, print that edge's pair 
        An Adjacency Matrix? find that vertex's row, and print all non-nil items in that row (all vertices with connections)
        An Adjacency List? find the vertex in the hash list and print all nodes included in the chain
