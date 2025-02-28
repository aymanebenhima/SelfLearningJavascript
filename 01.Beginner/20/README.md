### Exercise: Find the missing number in an array

#### Task:
Write a JavaScript function named `findMissingNumber` that takes an array of integers from 1 to n as input and returns the missing number.

#### Expected Result:
For example, if the input array is `[1, 2, 4, 5, 6]`, the expected result should be:
```
The missing number is: 3
```
If the input array is `[1, 2, 3, 4, 6, 7, 8]`, the expected result should be:
```
The missing number is: 5
```

#### Hints:
1. Calculate the sum of all integers from 1 to n using the formula `n * (n + 1) / 2`.
2. Iterate through the given array and calculate the sum of its elements.
3. Subtract the sum of the given array from the sum of all integers from 1 to n to find the missing number.
4. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is an array containing integers from 1 to n.
- Allow the user to input the array using prompts.
- Test the function with different input arrays to verify its correctness.


## Solution

<details>
  <summary>Click For Solution</summary>

```JS

const findMissingNumber = (input) => {

  const n = input.length + 1;
  let expectedsum = (n * (n + 1)) / 2; 
  let actualsum = 0;

  
  for (let num of input) {
    actualsum += num;
  }

  const Missingnumber = expectedsum - actualsum;

  return `The missing number is: ${Missingnumber}`;
}


console.log(findMissingNumber([1,2,4])) // Output The missing number is : 3

```

[Previous Exercise](../19/README.md) | [Index](../../README.md) | [Next Exercise](../../02.Intermediate/1/README.md)