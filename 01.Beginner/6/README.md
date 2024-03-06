### Exercise: Find the maximum and minimum elements in an array

#### Task:
Write a JavaScript function named `findMinMaxElements` that takes an array of numbers as input and returns an object containing the maximum and minimum elements in the array.

#### Expected Result:
For example, if the input array is `[3, 7, 2, 9, 4]`, the expected result should be:
```
For the array [3, 7, 2, 9, 4]:
- Maximum element: 9
- Minimum element: 2
```
If the input array is `[15, 27, 10, 35, 20, 45]`, the expected result should be:
```
For the array [15, 27, 10, 35, 20, 45]:
- Maximum element: 45
- Minimum element: 10
```

#### Hints:
1. Initialize variables to store the maximum and minimum elements, initially set to the first element of the array.
2. Iterate through the array and update the maximum and minimum elements as you go.
3. Use an object to return the maximum and minimum elements together.
4. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is an array of numbers.
- Allow the user to input the array using prompts.
- Test the function with different input arrays to verify its correctness.