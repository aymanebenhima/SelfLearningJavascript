### Exercise: Find the largest element in an array

#### Task:
Write a JavaScript function named `findLargestElement` that takes an array of numbers as input and returns the largest element in the array.

#### Expected Result:
For example, if the input array is `[3, 7, 2, 9, 4]`, the expected result should be:
```
The largest element in the array [3, 7, 2, 9, 4] is 9.
```
If the input array is `[15, 27, 10, 35, 20, 45]`, the expected result should be:
```
The largest element in the array [15, 27, 10, 35, 20, 45] is 45.
```

#### Hints:
1. Iterate through the array and keep track of the largest element found so far.
2. Initialize a variable to store the largest element and update it as you iterate through the array.
3. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is an array of numbers.
- Allow the user to input the array using prompts.
- Test the function with different input arrays to verify its correctness.



## Solution

<details>
  <summary>Click For Solution</summary>

```JS
consgt findLargestElement = (array) => {

      if (!Array.isArray(array)) {
        return "Please enter a valid array.";
    }


    let max = array[0];


    for(let i = 0 ; i < array.length ; i++){
        if(array[i] > max){
            max = array[i];
        }
    }


    return max;
}



console.log(findLargestElement([8,-4,0,8,4,66])); // output 66

```

[Previous Exercise](../04/README.md) | [Index](../../README.md) | [Next Exercise](../06/README.md)