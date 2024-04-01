## JavaScript Array Manipulation Problems

This part contains 10 problems focusing on JavaScript array manipulations. For each problem, two solutions are provided: the first solution utilizes array methods, while the second solution accomplishes the task without using any built-in array methods.

### Problems List:

1. **Sum of All Numbers in an Array**
2. **Remove Duplicates from an Array**
3. **Find the Maximum Number in an Array**
4. **Sort an Array of Strings Alphabetically**
5. **Find the Index of a Specific Element in an Array**
6. **Average of All Numbers in an Array**
7. **Merge Two Arrays and Remove Duplicates**
8. **Check if All Elements in an Array are Even**
9. **Count the Occurrences of Each Element in an Array**
10. **Flatten a Nested Array**

Each problem comes with detailed explanations and code examples for both the array method solution and the solution without using array methods.

---

**1. Sum of All Numbers in an Array**
*Description: Calculate the sum of all numbers in a given array.*

```js
const numbers = [1, 2, 3, 4, 5];
// const sum = [in oneline]
console.log(sum); // Output : 15
```

**2. Remove Duplicates from an Array**
*Description: Remove duplicate elements from a given array while preserving the order of elements.*
```js
const duplicates = [1, 2, 2, 3, 4, 4, 5];
// const unique = [in oneline]
console.log(unique); // Output: [1, 2, 3, 4, 5]
```

**3. Find the Maximum Number in an Array**
*Description: Find the maximum number in a given array.*
```js
const numbers = [1, 3, 2, 5, 4];
// const max = [in oneline];
console.log(max); // Output: 5
```

**4. Sort an Array of Strings Alphabetically**
*Description: Sort an array of strings alphabetically.*
```js
const fruits = ['banana', 'apple', 'orange', 'grape'];
// ine oneline
console.log(fruits); // Output: ['apple', 'banana', 'grape', 'orange']
```

**5. Find the Index of a Specific Element in an Array**
*Description: Find the index of a specific element in a given array.*

```js
const numbers = [10, 20, 30, 40, 50];
//const index = (numbers, target) => [in oneline];
console.log(index(numbers, 30)); // Output: 2
```

**6. Average of All Numbers in an Array**
*Description: Calculate the average of all numbers in a given array.*
```js
// const calculateAverage = arr => [in oneline]
const numbers = [10, 20, 30, 40, 50];
console.log(calculateAverage(numbers)); // Output: 30
```

**7. Merge Two Arrays and Remove Duplicates**
*Description: Merge two arrays and remove duplicate elements while preserving the order of elements.*
```js
// const mergeAndRemoveDuplicates = (arr1, arr2) => [in oneline]
const arr1 = [1, 2, 3];
const arr2 = [3, 4, 5];
console.log(mergeAndRemoveDuplicates(arr1, arr2)); // Output: [1, 2, 3, 4, 5]
```

**8. Check if All Elements in an Array are Even**
*Description: Check if all elements in a given array are even numbers.*
```js
// const areAllEven = arr => [in oneline]
const numbers = [2, 4, 6, 8, 10];
console.log(areAllEven(numbers)); // Output: true
```

**9. Count the Occurrences of Each Element in an Array**
*Description: Count the occurrences of each element in a given array and return an object with element counts.*
```js
// const countOccurrences = arr => [in oneline]
const fruits = ['apple', 'banana', 'apple', 'orange', 'banana'];
console.log(countOccurrences(fruits)); // Output: { apple: 2, banana: 2, orange: 1 }
```

**10. Flatten a Nested Array**
*Description: Flatten a nested array into a single-level array.*
```js
// const flattenArray = () => [in oneline]
const nestedArray = [[1, 2], [3, 4], [5, 6]];
console.log(flattenArray(nestedArray)); // Output: [1, 2, 3, 4, 5, 6]
```