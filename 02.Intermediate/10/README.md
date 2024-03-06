### Exercise: Perform a breadth-first search (BFS) on a graph

#### Task:
Write a JavaScript function named `breadthFirstSearch` that takes a graph represented as an adjacency list and a starting vertex as input, and performs a breadth-first search (BFS) traversal.

#### Expected Result:
For example, if the input graph is represented as follows:
```javascript
const graph = {
    0: [1, 2],
    1: [0, 3, 4],
    2: [0, 4],
    3: [1, 5],
    4: [1, 2, 5],
    5: [3, 4]
};
```
and the starting vertex is `0`, the expected result should be:
```
Breadth-first traversal starting from vertex 0: 0, 1, 2, 3, 4, 5
```

#### Hints:
1. Use a queue data structure to keep track of vertices to visit.
2. Start by enqueueing the starting vertex.
3. Iterate through the vertices in the queue, enqueueing adjacent vertices and marking them as visited.
4. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input values are valid.
- Allow the user to input the graph and starting vertex.
- Test the function with different graphs and starting vertices to verify its correctness.
