## Introduction to the Basic Data Structure Challenges
---
## Basic Data Structures: Use an Array to Store a Collection of Data
```js
/*We have defined a variable called yourArray. Complete the statement by assigning an array of at least 5 elements in length to the yourArray variable. Your array should contain at least one string, one number, and one boolean.

yourArray is an array
yourArray is at least 5 elements long
yourArray contains at least one boolean
yourArray contains at least one number
yourArray contains at least one string*/

let yourArray; // change this line

// SOLUTION
let yourArray = ["1", 2, true, undefined, null]; // change this line
```
---
---
## Basic Data Structures: Access an Array's Contents Using Bracket Notation
```js
//In order to complete this challenge, set the 2nd position (index 1) of myArray to anything you want, besides "b".
/*myArray[0] is equal to "a"
myArray[1] is no longer set to "b"
myArray[2] is equal to "c"
myArray[3] is equal to "d"*/

let myArray = ["a", "b", "c", "d"];
// change code below this line

//change code above this line
console.log(myArray);

// SOLUTION

let myArray = ["a", "b", "c", "d"];
// change code below this line
myArray[1] = "e"
//change code above this line
console.log(myArray);


```
---
---
## Basic Data Structures: Add Items to an Array with push() and unshift()
```js
/*We have defined a function, mixedNumbers, which we are passing an array as an argument. Modify the function by using push() and unshift() to add 'I', 2, 'three' to the beginning of the array and 7, 'VIII', 9 to the end so that the returned array contains representations of the numbers 1-9 in order.*/

function mixedNumbers(arr) {
  // change code below this line

  // change code above this line
  return arr;
}

// do not change code below this line
console.log(mixedNumbers(['IV', 5, 'six']));

// SOLUTION

function mixedNumbers(arr) {
  // change code below this line
 /*arr.unshift("three");
  arr.unshift(2);
  arr.unshift("I");
  arr.push(7);
  arr.push("VIII");
  arr.push(9);*/
  arr.unshift('I', 2, 'three');
  arr.push(7, 'VIII', 9);
  // change code above this line
  return arr;
}

// do not change code below this line
console.log(mixedNumbers(['IV', 5, 'six']));
```
---
---
## Basic Data Structures: Remove Items from an Array with pop() and shift()
```js
/*We have defined a function, popShift, which takes an array as an argument and returns a new array. Modify the function, using pop() and shift(), to remove the first and last elements of the argument array, and assign the removed elements to their corresponding variables, so that the returned array contains their values.
popShift(["challenge", "is", "not", "complete"]) should return ["challenge", "complete"]
The popShift function should utilize the pop() method
The popShift function should utilize the shift() method
*/
function popShift(arr) {
  let popped; // change this line
  let shifted; // change this line
  return [shifted, popped];
}

// do not change code below this line
console.log(popShift(['challenge', 'is', 'not', 'complete']));

// SOLUTION

function popShift(arr) {
  let popped = arr.pop(); // change this line
  let shifted = arr.shift(); // change this line
  return [shifted, popped];
}

// do not change code below this line
console.log(popShift(['challenge', 'is', 'not', 'complete']));
```
---
---
## Basic Data Structures: Remove Items Using splice()
```js
/*We've defined a function, sumOfTen, which takes an array as an argument and returns the sum of that array's elements. Modify the function, using splice(), so that it returns a value of 10.
sumOfTen should return 10
The sumOfTen function should utilize the splice() method*/

// do not change code below this lineconsole.log(sumOfTen([2, 5, 1, 5, 2, 1]));}     // change code above this line  return arr.reduce((a, b) => a + b);function sumOfTen(arr) {  // change code below this line
function sumOfTen(arr) {
  // change code below this line
  
  // change code above this line
  return arr.reduce((a, b) => a + b);
}

// do not change code below this line
console.log(sumOfTen([2, 5, 1, 5, 2, 1]));

// SOLUTION

function sumOfTen(arr) {
  // change code below this line
  arr.splice(1,2);
  // change code above this line
  return arr.reduce((a, b) => a + b);
}

// do not change code below this line
console.log(sumOfTen([2, 5, 1, 5, 2, 1]));

```
---
---
## Basic Data Structures: Add Items Using splice()
```js
/*We have defined a function, htmlColorNames, which takes an array of HTML colors as an argument. Modify the function using splice() to remove the first two elements of the array and add 'DarkSalmon' and 'BlanchedAlmond' in their respective places.
htmlColorNames should return ["DarkSalmon", "BlanchedAlmond", "LavenderBlush", "PaleTurqoise", "FireBrick"]
Passed
The htmlColorNames function should utilize the splice() method
Passed
You should not use shift() or unshift().
Passed
You should not use array bracket notation.*/
// SOLUTION
function htmlColorNames(arr) {
  // change code below this line
  arr.splice(0, 2, 'DarkSalmon', 'BlanchedAlmond');
  // change code above this line
  return arr;
} 
 
// do not change code below this line
console.log(htmlColorNames(['DarkGoldenRod', 'WhiteSmoke', 'LavenderBlush', 'PaleTurqoise', 'FireBrick']));
```
---
---
##
```js
```
---
---
##
```js
```
---
---
##
```js
```
---
---
##
```js
```
---
---
##
```js
```
---
---
##
```js
```
---
---
##
```js
```
---
---
##
```js
```
---
---
##
```js
```
---
---
##
```js
```
---
---
##
```js
```
---
---
##
```js
```
---
---
##
```js
```
---
---
##
```js
```
---
---
##
```js
```
