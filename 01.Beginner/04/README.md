### Exercise: Reverse a string

#### Task:
Write a JavaScript function named `reverseString` that takes a string as input and returns the reversed version of the string.

#### Expected Result:
For example, if the input string is "hello", the expected result should be:
```
The reversed string of "hello" is "olleh".
```
If the input string is "javascript", the expected result should be:
```
The reversed string of "javascript" is "tpircsavaj".
```

#### Hints:
1. Use the `split()`, `reverse()`, and `join()` methods to reverse the string.
2. Remember that strings are immutable, so you need to convert the string to an array of characters first.
3. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is a string.
- Allow the user to input the string using a prompt.
- Test the function with different input values to verify its correctness.

## Solution

<details>
  <summary>Click For Solution</summary>

```JS
const reverseString = (str) => {

    if(typeof str !== 'string'){
        return "Please enter a valid string";
    }

    let reversedString = "";
    for(let i = str.length - 1 ; i >=0 ; i--){
            reversedString+=str[i];
    }

    return reversedString;

}



console.log(reverseString(7)); /// Invalid String
console.log(reverseString("javascript")); /// tpircsavaj

```




[Previous Exercise](../03/README.md) | [Index](../../README.md) | [Next Exercise](../05/README.md)