### Exercise: Check if a given string is a valid hexadecimal color code

#### Task:
Write a JavaScript function named `isValidHexColor` that takes a string as input and returns `true` if it's a valid hexadecimal color code, and `false` otherwise.

#### Expected Result:
For example, if the input string is "#FFA500", the expected result should be:
```
The string "#FFA500" is a valid hexadecimal color code: true
```
If the input string is "blue", the expected result should be:
```
The string "blue" is a valid hexadecimal color code: false
```

#### Hints:
1. Use regular expressions to validate the hexadecimal color code format.
2. The regular expression pattern for a valid hexadecimal color code is `^#?([a-fA-F0-9]{3}|[a-fA-F0-9]{6})$`.
3. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Allow for both 3-digit and 6-digit hexadecimal color codes.
- Allow the user to input the color code using prompts.
- Test the function with different input strings to verify its correctness.
