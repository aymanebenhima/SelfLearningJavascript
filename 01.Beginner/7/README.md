### Exercise: Check if a given year is a leap year

#### Task:
Write a JavaScript function named `isLeapYear` that takes a year as input and returns `true` if it's a leap year, and `false` otherwise.

#### Expected Result:
For example, if the input year is 2020, the expected result should be:
```
2020 is a leap year.
```
If the input year is 2021, the expected result should be:
```
2021 is not a leap year.
```

#### Hints:
1. A leap year is either divisible by 4 and not divisible by 100, or divisible by 400.
2. Use the modulo operator (`%`) to check if the year is divisible evenly by 4, 100, and 400.
3. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is a valid year.
- Allow the user to input the year using prompts.
- Test the function with different input years to verify its correctness.
