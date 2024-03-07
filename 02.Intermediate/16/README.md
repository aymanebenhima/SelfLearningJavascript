### Exercise: Find the intersection of two sorted arrays

#### Task:
Write a JavaScript function named `findIntersection` that takes two sorted arrays as input and returns an array containing elements that are present in both arrays.

#### Expected Result:
For example, if the input arrays are `[1, 2, 3, 4, 5]` and `[3, 4, 5, 6, 7]`, the expected result should be:
```
Intersection: [3, 4, 5]
```
If the input arrays are `[-1, 0, 1, 2]` and `[1, 2, 3, 4]`, the expected result should be:
```
Intersection: [1, 2]
```

#### Hints:
1. Initialize two pointers to traverse both arrays simultaneously.
2. Compare elements at the current positions of the pointers.
3. If the elements are equal, add them to the intersection array and move both pointers forward.
4. If one element is greater than the other, move the pointer of the smaller element forward.
5. Repeat until one of the arrays is fully traversed.
6. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input values are arrays.
- Allow the user to input the arrays using prompts.
- Test the function with different input arrays to verify its correctness.


[Previous Exercise](../15/README.md) | [Index](../../README.md) | [Next Exercise](../17/README.md)