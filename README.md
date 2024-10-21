Graph Data Structure Project

#### Overview
This project explores the implementation and manipulation of graph data structures in Python, focusing on concepts like nodes, edges, and graph traversal techniques. The notebook showcases how to efficiently model and represent graphs using Python libraries, emphasizing algorithms and methods crucial for understanding the fundamentals of graphs.

#### Project Structure
1. **Graph Construction**: Builds the fundamental graph structure, defining nodes and edges while allowing flexible representations (like adjacency lists).
2. **Algorithms and Operations**: Includes basic and advanced graph algorithms such as Depth-First Search (DFS), Breadth-First Search (BFS), and handling weighted edges.
3. **Visualization**: Utilizes the `graphviz` library to visualize the graph, aiding in understanding complex relationships between nodes.

#### Key Concepts Covered
- **Nodes and Edges**: Core building blocks of a graph, representing entities and their relationships.
- **Graph Representation**: Uses various methods like adjacency lists for efficiently storing and accessing graph information.
- **Graph Traversal Algorithms**:
  - **Breadth-First Search (BFS)**: Explores all nodes level by level, useful for finding the shortest path in unweighted graphs.
  - **Depth-First Search (DFS)**: Explores nodes by going as deep as possible, often used for connectivity checks or cycle detection.
- **Shortest Path Algorithms**: Implements algorithms for finding shortest paths between nodes in a weighted graph.
- **Graph Visualizations**: Leverages `graphviz` to provide a visual representation of nodes and edges, enhancing comprehension.

#### Tech Stack
- **Python**: Core language used for the project.
- **Libraries**: Utilizes `graphviz` for graph visualization and core Python modules like `math` for computations.

#### Prerequisites
- Python 3.x
- Install necessary libraries:
  ```bash
  pip install graphviz
  ```

#### How to Run the Notebook
1. Clone the repository and set up the project directory.
2. Adjust the base directory paths for input and output in the notebook:
   ```python
   inputFileBase = "<path_to_input_files>"
   outputFileBase = "<path_to_output_files>"
   ```
3. Execute the notebook sequentially to explore the implementation of graph data structures and algorithms.

#### Usage
- **Input and Output Files**: Provide input files containing graph data in the specified format within the notebook. The output files will be saved at the designated paths for results and visualizations.
- **Custom Modifications**: Users can modify the graph data, edge weights, or traversal algorithms as needed.

#### Concepts Highlighted in the Project
- **Inheritance and Enums**: Implements enums to define graph-related properties and uses inheritance to extend core graph functionalities.
- **Mathematical Concepts**: Handles operations involving infinity for algorithms like Dijkstra’s.
- **Exception Handling**: Ensures robust handling of edge cases and erroneous inputs.

This project offers a comprehensive understanding of graph theory and its applications, making it a valuable resource for data science and algorithm enthusiasts.

Feel free to explore the code to get insights into graph structures and traversal methods!
