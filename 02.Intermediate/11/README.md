### Problem: Implement a function to merge two sorted arrays into a single sorted array.

#### Task:
Write a JavaScript function named `mergeSortedArrays` that takes two sorted arrays as input and merges them into a single sorted array.

#### Example:
```javascript
Input:
Array 1: [1, 3, 5, 7, 9]
Array 2: [2, 4, 6, 8, 10]
Output: Merged array: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

Input:
Array 1: [2, 4, 6, 8]
Array 2: [1, 3, 5, 7, 9]
Output: Merged array: [1, 2, 3, 4, 5, 6, 7, 8, 9]
```

#### Hints:
1. Initialize an empty array to store the merged result.
2. Use two pointers to traverse both arrays simultaneously.
3. Compare elements at the current positions of the pointers and push the smaller element into the result array.
4. Move the pointer of the array from which the smaller element was taken forward.
5. Repeat until one of the arrays is fully traversed.
6. Append the remaining elements of the non-empty array to the result array.
7. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input values are arrays.
- Allow the user to input the arrays using prompts.
- Test the function with different input arrays to verify its correctness.


[Previous Exercise](../10/README.md) | [Index](../../README.md) | [Next Exercise](../12/README.md)