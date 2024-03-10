### Exercise: Reverse words in a sentence

#### Task:
Write a JavaScript function named `reverseWords` that takes a sentence as input and returns a new sentence with the words reversed.

#### Expected Result:
For example, if the input sentence is "Hello world!", the expected result should be:
```
Reversed sentence: "olleH !dlrow"
```
If the input sentence is "JavaScript is awesome", the expected result should be:
```
Reversed sentence: "tpircSavaJ si emosewa"
```

#### Hints:
1. Use the `split()` method to split the sentence into an array of words.
2. Use the `reverse()` method to reverse the order of the words in the array.
3. Use the `join()` method to join the reversed words back into a sentence.
4. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is a string.
- Allow the user to input the sentence using prompts.
- Test the function with different input sentences to verify its correctness.

## Solution

<details>
  <summary>Click For Solution</summary>

```JS
const reverseWords = (str) => {

    const array = str.split(" ");
    
    let reversedwords = [];

    for(let item of array){
        
        let strword = "";
        for(let i = item.length - 1 ; i>=0 ; i--){
            strword+=item[i];
        }
        reversedwords.push(strword);
    }

    return reversedwords.join(" ");  
}


console.log(reverseWords("hello world"));

```


[Previous Exercise](../07/README.md) | [Index](../../README.md) | [Next Exercise](../09/README.md)