### Exercise: Create a function to check if a number is even or odd

#### Task:
Write a JavaScript function named `isEvenOrOdd` that takes a number as input and returns a message indicating whether the number is even or odd.

#### Expected Result:
For example, if the input number is 7, the expected result should be:
```
7 is odd.
```
If the input number is 10, the expected result should be:
```
10 is even.
```

#### Hints:
1. Use the modulo operator (`%`) to determine if the number is divisible by 2.
2. If the remainder is 0, the number is even; otherwise, it's odd.
3. Use `if` statements or ternary operators to implement the logic.

#### Additional Tasks (Optional):
- Add validation to ensure that the input value is a number.
- Allow the user to input the number using a prompt.
- Test the function with different input values to verify its correctness.


## Solution

<details>
  <summary>Click For Solution</summary>

```JS
const isEvenOrOdd = (n) => {

    if(typeof n !== 'number'){
        return "please enter a valid number !";
    }

    return n % 2 == 0 ? "even" : "odd"
}

console.log(isEvenOrOdd(4)); // even
console.log(isEvenOrOdd("2")); // Invalid Number
console.log(isEvenOrOdd(7)); // odd

```




[Previous Exercise](../02/README.md) | [Index](../../README.md) | [Next Exercise](../04/README.md)