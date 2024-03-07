### Exercise: Rotate elements of an array to the left

#### Task:
Write a JavaScript function named `rotateLeft` that takes an array and a number of positions as input and rotates the elements of the array to the left by the specified number of positions.

#### Expected Result:
For example, if the input array is `[1, 2, 3, 4, 5]` and the number of positions is `2`, the expected result should be:
```
Rotated array: [3, 4, 5, 1, 2]
```
If the input array is `[1, 2, 3, 4, 5]` and the number of positions is `3`, the expected result should be:
```
Rotated array: [4, 5, 1, 2, 3]
```

#### Hints:
1. Use array slicing to split the array into two parts: elements to be rotated and elements to remain in their original positions.
2. Concatenate the sliced parts in the desired order to form the rotated array.
3. Use modular arithmetic to handle cases where the number of positions is greater than the length of the array.
4. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is an array and the number of positions is a positive integer.
- Allow the user to input the array and number of positions using prompts.
- Test the function with different input arrays and numbers of positions to verify its correctness.


[Previous Exercise](../13/README.md) | [Index](../../README.md) | [Next Exercise](../15/README.md)