# THE-METRO-MAZE

A simple Java Application is designed to gather user-input information, namely the names of the source and destination stations within the NYC Subway Metro. The program then computes and displays both the fare and the shortest metro route for the commuter's convenience. To aid navigation, a metro map is also incorporated. The underlying concept employs Graph and Heap data structures, where nodes signify metro stations with pertinent details such as name, corridor, and connected lines. The edges, representing connections between nodes, denote the distance between stations. The cost of each edge equals the distance between the connecting stations (nodes). Various algorithms, including Dijkstra, breadth-first search, and depth-first search, are utilized to ascertain the shortest path between the source and destination stations. The fare is computed based on the total distance between the two stations. The program then presents the metro route and the corresponding total fare. The primary code resides in Main.java, encompassing crucial functionalities, while Heap.java focuses on the implementation of the heap structure.
