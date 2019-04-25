   ### Introduction to the Basic Data Structure Challenges
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
