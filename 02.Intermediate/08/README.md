### Exercise: Find the intersection of two arrays

#### Task:
Write a JavaScript function named `findIntersection` that takes two arrays as input and returns a new array containing elements that are common to both arrays.

#### Expected Result:
For example, if the input arrays are `[1, 2, 3, 4, 5]` and `[3, 4, 5, 6, 7]`, the expected result should be:
```
Intersection of [1, 2, 3, 4, 5] and [3, 4, 5, 6, 7] is: [3, 4, 5]
```
If the input arrays are `['a', 'b', 'c']` and `['b', 'c', 'd']`, the expected result should be:
```
Intersection of ['a', 'b', 'c'] and ['b', 'c', 'd'] is: ['b', 'c']
```
If there is no intersection, the expected result should be an empty array `[]`.

#### Hints:
1. Use a loop or built-in methods to iterate through the arrays.
2. Use an object or Set to keep track of elements in one array.
3. Check for the presence of each element in the second array.
4. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input values are arrays.
- Allow the user to input the arrays using prompts.
- Test the function with different input arrays to verify its correctness.


[Previous Exercise](../07/README.md) | [Index](../../README.md) | [Next Exercise](../09/README.md)