# Experiment 12(a): Prim's Minimum Spanning Tree (MST)

## Aim
To write a Python program for Prim's Minimum Spanning Tree (MST) algorithm.

---

## Algorithm

1. **Initialize Key Array**:
   - Initialize a `key` array to represent the minimum weight edge for each vertex, setting all values to infinity except for the first vertex, which is set to 0.

2. **Select the Minimum Key Vertex**:
   - Use the `minKey()` function to find the vertex with the smallest key value that is not yet included in the MST.

3. **Update Key Values**:
   - For each adjacent vertex of the selected vertex, if the edge weight is smaller than the current key value and the vertex is not in the MST, update the key value and parent of the vertex.

4. **Repeat**:
   - Repeat steps 2 and 3 for all vertices until all vertices are included in the MST.

5. **Print the MST**:
   - Finally, print the Minimum Spanning Tree using the parent array which holds the parent vertex for each vertex in the MST.

---

## Program

```
```

## OUTPUT

## RESULT
