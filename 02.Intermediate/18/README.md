### Exercise: Check if a string is a valid IPv4 address

#### Task:
Write a JavaScript function named `isValidIPv4` that takes a string as input and returns `true` if the string is a valid IPv4 address, and `false` otherwise.

#### Expected Result:
For example, if the input string is "192.168.0.1", the expected result should be:
```
"192.168.0.1" is a valid IPv4 address: true
```
If the input string is "256.0.0.1", the expected result should be:
```
"256.0.0.1" is a valid IPv4 address: false
```

#### Hints:
1. An IPv4 address consists of four numbers (octets) separated by periods.
2. Each octet must be a number between 0 and 255 inclusive.
3. Use regular expressions to validate the format of the string.
4. Split the string by periods and check each octet individually.
5. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is a string.
- Allow the user to input the string using prompts.
- Test the function with different input strings to verify its correctness.


[Previous Exercise](../17/README.md) | [Index](../../README.md) | [Next Exercise](../19/README.md)