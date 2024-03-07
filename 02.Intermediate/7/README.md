### Exercise: Check if a string is a palindrome

#### Task:
Write a JavaScript function named `isPalindrome` that takes a string as input and returns `true` if it is a palindrome ignoring spaces and punctuation, and `false` otherwise.

#### Expected Result:
For example, if the input string is "A man, a plan, a canal, Panama!", the expected result should be:
```
The string "A man, a plan, a canal, Panama!" is a palindrome: true
```
If the input string is "racecar", the expected result should be:
```
The string "racecar" is a palindrome: true
```
If the input string is "hello world", the expected result should be:
```
The string "hello world" is a palindrome: false
```

#### Hints:
1. Remove spaces and punctuation from the input string.
2. Convert the string to lowercase for case-insensitive comparison.
3. Use two pointers (one starting from the beginning and the other from the end) to compare characters.
4. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is a string.
- Allow the user to input the string using prompts.
- Test the function with different input strings to verify its correctness.


[Previous Exercise](../6/README.md) | [Index](../../README.md) | [Next Exercise](../8/README.md)