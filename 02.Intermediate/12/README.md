### Exercise: Find the longest common prefix among an array of strings

#### Task:
Write a JavaScript function named `longestCommonPrefix` that takes an array of strings as input and returns the longest common prefix among them.

#### Expected Result:
For example, if the input array is `["flower", "flow", "flight"]`, the expected result should be:
```
The longest common prefix is: fl
```
If the input array is `["dog", "racecar", "car"]`, the expected result should be:
```
The longest common prefix is: ""
```

#### Hints:
1. Start with the first string as the initial prefix.
2. Compare each character of the prefix with the corresponding character of the other strings.
3. Stop when a character mismatch is found or when the end of any string is reached.
4. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is an array of strings.
- Allow the user to input the array using prompts.
- Test the function with different input arrays to verify its correctness.
