### Exercise: Check if a number is a perfect number

#### Task:
Write a JavaScript function named `isPerfectNumber` that takes a number as input and returns `true` if it is a perfect number, and `false` otherwise.

#### Expected Result:
For example, if the input number is 28, the expected result should be:
```
The number 28 is a perfect number: true
```
If the input number is 6, the expected result should be:
```
The number 6 is a perfect number: true
```
If the input number is 12, the expected result should be:
```
The number 12 is a perfect number: false
```

#### Hints:
1. A perfect number is a positive integer that is equal to the sum of its proper divisors excluding itself.
2. Iterate through the numbers from 1 to (n/2) and check if they are divisors of the given number.
3. Sum up the divisors and compare it with the input number.
4. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is a positive integer.
- Allow the user to input the number using prompts.
- Test the function with different input numbers to verify its correctness.
