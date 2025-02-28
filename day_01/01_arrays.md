## 💻 Exercises:Day 01 - Arrays

### Exercise: Level 1

```js
const countries = [
  'Albania',
  'Bolivia',
  'Canada',
  'Denmark',
  'Ethiopia',
  'Finland',
  'Germany',
  'Hungary',
  'Ireland',
  'Japan',
  'Kenya'
]

const webTechs = [
  'HTML',
  'CSS',
  'JavaScript',
  'React',
  'Redux',
  'Node',
  'MongoDB'
]
```

- Declare an empty array
- Declare an array with more than 5 number of elements
- Find the length of your array
- Get the first item, the middle item and the last item of the array
- Declare an array called `mixedDataTypes`, put different data types in the array and find the length of the array. The array size should be greater than 5
- Declare an array variable name `itCompanies` and assign initial values `Facebook`, `Google`, `Microsoft`, `Apple`, `IBM`, `Oracle` and `Amazon`
- Print the array using `console.log()`
- Print the number of companies in the array
- Print the first company, middle and last company
- Print out each company
- Change each company name to uppercase one by one and print them out
- Print the array like a sentence: `Facebook, Google, Microsoft, Apple, IBM, Oracle and Amazon are big IT companies.`
- Check if a certain company exists in the `itCompanies` array. If it exists, return the company else return "Company is not found"
- Filter out companies which have more than one 'o' without the `filter` method
- Sort the array using `sort()` method
- Reverse the array using `reverse()` method
- Slice out the first 3 companies from the array
- Slice out the last 3 companies from the array
- Slice out the middle IT company or companies from the array
- Remove the first IT company from the array
- Remove the middle IT company or companies from the array
- Remove the last IT company from the array
- Remove all IT companies

---

### Exercise: Level 2

- First remove all the punctuations and change the string to array and count the number of words in the array

```js
let text = 'I love teaching and empowering people. I teach HTML, CSS, JS, React, Python.'
console.log(words)
console.log(words.length)
```

Expected output:
```js
["I", "love", "teaching", "and", "empowering", "people", "I", "teach", "HTML", "CSS", "JS", "React", "Python"]
13
```

- In the following shopping cart add, remove, edit items:

```js
const shoppingCart = ['Milk', 'Coffee', 'Tea', 'Honey']
```

  - Add 'Meat' at the beginning of your shopping cart if it has not been already added
  - Add 'Sugar' at the end of your shopping cart if it has not been already added
  - Remove 'Honey' if you are allergic to honey
  - Modify 'Tea' to 'Green Tea'

- In `countries` array check if 'Ethiopia' exists in the array. If it exists, print 'ETHIOPIA'. If it does not exist, add it to the countries list.

- In the `webTechs` array check if `Sass` exists in the array. If it exists, print `'Sass is a CSS preprocess'`. If it does not exist, add `Sass` to the array and print the array.

- Concatenate the following two variables and store them in a `fullStack` variable.

```js
const frontEnd = ['HTML', 'CSS', 'JS', 'React', 'Redux']
const backEnd = ['Node', 'Express', 'MongoDB']

console.log(fullStack)
```

Expected output:
```js
["HTML", "CSS", "JS", "React", "Redux", "Node", "Express", "MongoDB"]
```

---

### Exercise: Level 3

- The following is an array of 10 students' ages:

```js
const ages = [19, 22, 19, 24, 20, 25, 26, 24, 25, 24]
```

  - Sort the array and find the min and max age
  - Find the median age (one middle item or two middle items divided by two)
  - Find the average age (sum of all items divided by number of items)
  - Find the range of the ages (max minus min)
  - Compare the value of `(min - average)` and `(max - average)`, use `abs()` method

- Slice the first ten countries from the `countries` array
- Find the middle country(ies) in the `countries` array
- Divide the `countries` array into two equal arrays if it is even. If `countries` array is not even, one more country should be in the first half.
