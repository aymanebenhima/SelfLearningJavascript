### Exercise: Capitalize the first letter of each word in a sentence

#### Task:
Write a JavaScript function named `capitalizeFirstLetter` that takes a sentence as input and returns a new sentence where the first letter of each word is capitalized.

#### Expected Result:
For example, if the input sentence is "hello world", the expected result should be:
```
Original sentence: hello world
Capitalized sentence: Hello World
```
If the input sentence is "javascript is awesome", the expected result should be:
```
Original sentence: javascript is awesome
Capitalized sentence: Javascript Is Awesome
```

#### Hints:
1. Use the `split()` method to split the sentence into an array of words.
2. Iterate through the array and capitalize the first letter of each word.
3. Use the `charAt()` and `toUpperCase()` methods to capitalize the first letter.
4. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is a string.
- Allow the user to input the sentence using prompts.
- Test the function with different input sentences to verify its correctness.


## Solution

<details>
  <summary>Click For Solution</summary>

```JS
const capitalizeFirstLetter = (str) => {
    
    let array = str.split(" ");
    
    let capitalize = [];
    
    for(let item of array){
        capitalize.push(item.charAt(0).toUpperCase() + item.slice(1));
    }
    
    
    return capitalize.join(" ");
    
    
}

console.log(capitalizeFirstLetter("hello world")); 

```

[Previous Exercise](../09/README.md) | [Index](../../README.md) | [Next Exercise](../11/README.md)