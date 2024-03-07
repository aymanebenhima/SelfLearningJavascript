### Exercise: Check if a string contains only alphanumeric characters

#### Task:
Write a JavaScript function named `isAlphanumeric` that takes a string as input and returns `true` if it contains only alphanumeric characters (letters and digits), and `false` otherwise.

#### Expected Result:
For example, if the input string is "hello123", the expected result should be:
```
The string "hello123" contains only alphanumeric characters: true
```
If the input string is "hello$world", the expected result should be:
```
The string "hello$world" contains only alphanumeric characters: false
```

#### Hints:
1. Use regular expressions to check if the string matches the pattern of alphanumeric characters.
2. The regular expression pattern for alphanumeric characters is `^[a-zA-Z0-9]+$`.
3. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is a string.
- Allow the user to input the string using prompts.
- Test the function with different input strings to verify its correctness.


[Previous Exercise](../14/README.md) | [Index](../../README.md) | [Next Exercise](../16/README.md)