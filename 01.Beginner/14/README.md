### Exercise: Remove all duplicates from an array

#### Task:
Write a JavaScript function named `removeDuplicates` that takes an array as input and returns a new array with all duplicate elements removed.

#### Expected Result:
For example, if the input array is `[1, 2, 3, 2, 4, 1, 5]`, the expected result should be:
```
Original array: [1, 2, 3, 2, 4, 1, 5]
Array with duplicates removed: [1, 2, 3, 4, 5]
```
If the input array is `['a', 'b', 'c', 'a', 'd', 'b']`, the expected result should be:
```
Original array: ['a', 'b', 'c', 'a', 'd', 'b']
Array with duplicates removed: ['a', 'b', 'c', 'd']
```

#### Hints:
1. Use a loop to iterate through each element in the array.
2. Use an object or a Set to keep track of unique elements encountered.
3. Append each unique element to a new array.
4. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is an array.
- Allow the user to input the array using prompts.
- Test the function with different input arrays to verify its correctness.



## Solution

<details>
  <summary>Click For Solution</summary>

```JS
const removeDuplicates = (array) => {

   const  set = new Set()


    for (const item of array) {
        set.add(item);
    }


    return set;
}


console.log(removeDuplicates([1,5,4,4]));

```

[Previous Exercise](../13/README.md) | [Index](../../README.md) | [Next Exercise](../15/README.md)