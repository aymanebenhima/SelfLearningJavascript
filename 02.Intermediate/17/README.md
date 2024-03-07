### Exercise: Find the kth smallest element in an unsorted array

#### Task:
Write a JavaScript function named `findKthSmallest` that takes an unsorted array and a positive integer k as input and returns the kth smallest element in the array.

#### Expected Result:
For example, if the input array is `[7, 10, 4, 3, 20, 15]` and k is `3`, the expected result should be:
```
The 3rd smallest element is: 7
```
If the input array is `[8, 2, 6, 1, 9]` and k is `2`, the expected result should be:
```
The 2nd smallest element is: 2
```

#### Hints:
1. Use sorting techniques like quicksort or heapsort to sort the array.
2. After sorting, access the kth element of the sorted array to find the kth smallest element.
3. You can also use techniques like partitioning or min-heap to find the kth smallest element without fully sorting the array.
4. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is an array and k is a positive integer.
- Allow the user to input the array and k using prompts.
- Test the function with different input arrays and k values to verify its correctness.


[Previous Exercise](../16/README.md) | [Index](../../README.md) | [Next Exercise](../18/README.md)