### Exercise: Convert temperature between Celsius and Fahrenheit

#### Task:
Write a JavaScript function named `convertTemperature` that takes a temperature value, a unit to convert from, and a unit to convert to as input, and returns the converted temperature value.

#### Expected Result:
For example, if the input temperature value is 30, and units to convert from and to are 'C' (Celsius) and 'F' (Fahrenheit) respectively, the expected result should be:
```
30°C is equivalent to 86°F.
```
If the input temperature value is 86, and units to convert from and to are 'F' (Fahrenheit) and 'C' (Celsius) respectively, the expected result should be:
```
86°F is equivalent to 30°C.
```

#### Hints:
1. To convert Celsius to Fahrenheit: `(Celsius * 9/5) + 32`
2. To convert Fahrenheit to Celsius: `(Fahrenheit - 32) * 5/9`
3. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Add validation to ensure that the input values are valid (e.g., numeric temperature value, valid unit conversion).
- Allow the user to input the temperature and units using prompts.
- Test the function with different input values and units to verify its correctness.


## Solution

<details>
  <summary>Click For Solution</summary>

```JS
const  convertTemperature = (temperature, from, to) => {
  let convertedTemp;
  if (from === 'C' && to === 'F') {
    convertedTemp = (temperature * (9/5)) + 32;
  } else if (from === 'F' && to === 'C') {
    convertedTemp = (temperature - 32) * (5/9);
  } 
  return `${temperature}°${from} is equivalent to ${convertedTemp}°${to}.`;
}


console.log(convertTemperature(4 , "C" , "F")); // Output 4°C is equivalent to 39.2°F.

```

[Previous Exercise](../17/README.md) | [Index](../../README.md) | [Next Exercise](../19/README.md)