### Exercise: Check if a given string is a valid email address format

#### Task:
Write a JavaScript function named `isValidEmail` that takes a string as input and returns `true` if it's a valid email address format, and `false` otherwise.

#### Expected Result:
For example, if the input string is "example@example.com", the expected result should be:
```
The string "example@example.com" is a valid email address format: true
```
If the input string is "example.com", the expected result should be:
```
The string "example.com" is a valid email address format: false
```

#### Hints:
1. Use regular expressions to validate the email address format.
2. The regular expression pattern for a simple email address format is `^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$`.
3. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add more complex email address format validation.
- Allow the user to input the email address using prompts.
- Test the function with different input strings to verify its correctness.


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

[Previous Exercise](../15/README.md) | [Index](../../README.md) | [Next Exercise](../17/README.md)