### Exercise: Flatten a nested array

#### Task:
Write a JavaScript function named `flattenArray` that takes a nested array as input and returns a flat array containing all the elements.

#### Expected Result:
For example, if the input nested array is `[[1, 2, [3]], 4, [5, [6, 7]]]`, the expected result should be:
```
Flattened array: [1, 2, 3, 4, 5, 6, 7]
```
If the input nested array is `[[1], [2], [3], [4]]`, the expected result should be:
```
Flattened array: [1, 2, 3, 4]
```

#### Hints:
1. Use recursion to traverse each element of the nested array.
2. If an element is an array, recursively call the function to flatten it.
3. Concatenate the elements of the nested arrays into a single flat array.
4. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is an array.
- Allow the user to input the nested array using prompts.
- Test the function with different input nested arrays to verify its correctness.
