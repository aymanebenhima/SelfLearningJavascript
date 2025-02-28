### Exercise: Generate a random password

#### Task:
Write a JavaScript function named `generateRandomPassword` that takes a length as input and returns a random password of the specified length with alphanumeric characters and symbols.

#### Expected Result:
For example, if the input length is 10, the expected result could be:
```
Generated random password: g^6#Yd!4$p
```
If the input length is 8, the expected result could be:
```
Generated random password: 5uT#2@9b
```

#### Hints:
1. Use a combination of alphanumeric characters and symbols to generate the password.
2. You can use the ASCII table to generate symbols.
3. Use `Math.random()` to generate random characters.
4. Use `console.log()` to display the result.

#### Additional Tasks (Optional):
- Allow the user to specify whether to include uppercase and lowercase characters in the password.
- Allow the user to specify whether to include symbols in the password.
- Test the function with different input lengths to verify its correctness.


## Solution

<details>
  <summary>Click For Solution</summary>

```JS

const  generateRandomPassword = (length) => {
  const charset = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789!@#$%^&*()_+-=[]{}|;:'<>,.?/";

  let password = "";
  for (let i = 0; i < length; i++) {
    password += charset.charAt(Math.floor(Math.random() * charset.length));
  }

  return password;
}


console.log(generateRandomPassword(20)); 
```



[Previous Exercise](../18/README.md) | [Index](../../README.md) | [Next Exercise](../20/README.md)