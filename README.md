# symmetric_graph
This Python project generates a random undirected graph, analyzes its structure, and visualizes it. 
The code leverages basic graph theory concepts to create and explore graph representations

### functions overview
**lista_wierzcholkow(wierzcholki):** Generates a list of edges for the graph, randomly connecting vertices.

**konwert_ls(l):** Converts the graph dictionary into an edge list format, which is used for visualization.

**rysuj(x):** Visualizes the graph using a circular layout, displaying the nodes and their connections.

**odleglosci_graf(graf, start):** Calculates the shortest distance from the start vertex to all others using BFS.

**poziomy_odleglosci(odleglosci):** Groups vertices based on their distance from the start vertex.

**czy_symetryczny(graf):** Checks for missing symmetric edges in the graph.

**uzupelnij_przeciwbiezne(graf, krawedzie):** Adds missing symmetric edges to ensure the graph is undirected.
