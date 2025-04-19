# Experiment 12(e): Count the Number of Triangles in an Undirected Graph

## AIM
To write a Python program to count the number of triangles present in an undirected graph.

---

## Algorithm

1. **Input the Graph**:
   - Start by taking the number of vertices as input.
   - Represent the graph using an adjacency matrix where `graph[i][j]` indicates the presence of an edge between vertices `i` and `j`.

2. **Matrix Multiplication**:
   - Initialize matrices `aux2` and `aux3` for storing the square and cube of the adjacency matrix respectively.
   - Multiply the adjacency matrix (`graph`) with itself to compute `aux2 = graph^2`.
   - Multiply the result (`aux2`) with the adjacency matrix again to compute `aux3 = graph^3`.

3. **Trace Calculation**:
   - The trace of a matrix is the sum of its diagonal elements. The diagonal elements of `aux3` represent the number of paths of length 3 starting and ending at each vertex.
   - Compute the trace of `aux3` to find the total number of triangles.

4. **Divide by 6**:
   - The number of triangles is the trace of `aux3` divided by 6. This is because each triangle is counted six times in the trace.

5. **Return the Result**:
   - The program outputs the number of triangles present in the undirected graph.

---

## Program
```
```

## OUTPUT


## RESULT
