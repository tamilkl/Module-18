# Experiment 12(b): Kruskal's Algorithm

## Aim
To write a Python program for Kruskal's algorithm to find the Minimum Spanning Tree (MST) of a given connected, undirected, and weighted graph.

---

## Algorithm

1. **Sort all edges**:
   - Sort all the edges in non-decreasing order of their weights.

2. **Initialize parent and rank arrays**:
   - Initialize the `parent` array to keep track of the set to which each vertex belongs.
   - Initialize the `rank` array to manage the union of sets efficiently.

3. **Iterate over sorted edges**:
   - Pick the smallest edge and check if it forms a cycle with the MST formed so far by checking if the vertices are in the same set.
   
4. **Check and add the edge**:
   - If it doesn't form a cycle, include this edge in the MST and perform a union of the two sets.

5. **Repeat until MST contains V-1 edges**:
   - Continue adding edges to the MST until it contains `V-1` edges, where `V` is the number of vertices.

6. **Print the MST**:
   - Finally, print the edges in the MST along with the minimum cost.

---

## Program

```

```

## OUTPUT

## RESULT
