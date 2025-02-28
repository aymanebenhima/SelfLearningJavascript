### Exercise: Calculate the sum of two numbers

#### Task:
Write a JavaScript program that calculates the sum of two numbers.

#### Expected Result:
For example, if the two numbers are 3 and 5, the expected result should be:
```
The sum of 3 and 5 is 8.
```

#### Hints:
1. Use variables to store the two numbers you want to add.
2. Use the addition operator (`+`) to calculate the sum of the two numbers.
3. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input values are numbers.
- Allow the user to input the two numbers using prompts.
- Create a function that takes two parameters (the two numbers) and returns the sum.


## Solution

<details>
  <summary>Click For Solution</summary>

```JS
 const sum = (n1,n2) => {
     return n1 + n2;
 }

 console.log(sum(5,5)) /// Output 10
```


[Previous Exercise](../01/README.md) | [Index](../../README.md) | [Next Exercise](../03/README.md)