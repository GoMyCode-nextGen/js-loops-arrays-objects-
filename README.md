# Array Iteration with while & for 
Exercises
## Basic Requirments
1.Write a function called arrayFor that takes an array as a parameter, loops through all the elements using For Loop and prints all elements of the array in the console using console.log.
```js
function arrayFor(array) {
   //Write your code here 
}  
arrayFor([1, 2, 3]) ->    1                           
2                           
3
```
2.Write a function called arrayWhile that takes an array as a parameter, loops through all the elements using While Loop and prints all elements of the array in the console using console.log.
```js

arrayWhile([1, 2, 3]) ->    1                           
2                           
3
```

3.Write a function called sum that takes an array of numbers as a parameter and returns the sum of the numbers in the array.
```js

function sum(array) {
   //Write your code here 
}  
sum([1, 2, 3]) -> 6 
sum([1, 2, 4]) -> 7
```
4.Write a function called sumEveryOther that takes an array of numbers as a parameter and returns the summation of every other number starting from the beginning of the array.
```js

function sumEveryOther(array) {
   //Write your code here 
}  
sumEveryOther([1, 2, 3, 4, 5]) -> 9 
sumEveryOther([1, 2, 4]) -> 5
```
5.Write a function called sumStartAt that takes an array of numbers, and an index as parameters and returns the summation of every number starting from the inputted index, until the end of the array.
```js

function sumStartAt(array, index) {
   //Write your code here 
}  
sumStartAt([1, 2, 3, 4, 5], 1) -> 14 
sumStartAt([1, 2, 4], 2) -> 4 
```
6.Write a function called sumUntil that takes an array of numbers, and an index as parameters and returns the summation of every number starting from the index 0, until the index parameter.
```js

function sumUntil(array, index) {
   //Write your code here
 }  
sumUntil([1, 2, 3, 4, 5], 2) -> 6 
sumUntil([1, 2, 4], 1) -> 3 
```
7.Write a function called subtractReverse that takes an array of numbers as a parameter and returns the subtraction of every number beginning at the last element of the input array and ending at the first element of the input array (in reverse).
```js

function subtractReverse(array) {
   //Write your code here 
}  
subtractReverse([1, 2, 3]) -> 0 
subtractReverse([0, 1, 2]) -> 1
```
8.Write a function called product that takes an array as a parameter and returns the product of all the elements in the array.
```js
function product(array) {
   //Write your code here 
}  
product([1, 2, 3]) -> 6 
product([0, -1, -2]) -> 0  
```
9.Write a function called average that takes an array as a parameter and returns the average of all the elements in the array.
```js

function average(array) {
   //Write your code here 
}  
average([1, 2, 3]) -> 2 
average([0, 1, 2]) -> 1 
```
10.Write a function called square that takes an array as a parameter and returns a new array where each element is the square of the element of the given array.
```js

function square(array) {
   //Write your code here 
}  
square([1, 2, 3]) -> [1, 4, 9] 
square([0, 1, 2]) -> [0, 1, 4]
```
11.Write a function called isArray that takes one parameter and returns true if the input is array otherwise returns false.
```js

function isArray(array) {
   //Write your code here 
}  
isArray([1, 2, 3]) -> true 
isArray("hi") -> false   
```
## More Practice

1.Write a function called min that takes an array as a parameter and returns the smallest number from the array.
```js

function min(array) {
   //Write your code here 
}  
min([1, 2, 3]) -> 1 
min([-1, 2, 3]) -> -1  
```
2.Write a function called max that takes an array as a parameter and returns the largest number from the array.
```js

function max(array) {
   //Write your code here 
}  
max([1, 2, 3]) -> 3 
max([1, -2, -3]) -> 1 
```
3.Write a function called shortestString that takes an array of strings as a parameter and returns the length of the shortest string in the given array.
```js

function shortestString(array) {
   //Write your code here 
}  
shortestString(["hi", "cat", "hello"]) -> 2 
shortestString(["lol", "kitty", "hey"]) -> 3    
```
4.Write a function called longestString that takes an array of strings as a parameter and returns the length of the longest string in the given array.
```js

function longestString(array) {
   //Write your code here 
}  
longestString(["hi", "cat", "hello"]) -> 5 
longestString(["lol", "cuttie", "hey"]) -> 6  
```
5.Write a function called shortestLongest that takes an array of strings as a parameter and returns a new array with the shortest and the longest string in the array.
```js

function shortestLongest(array) {
   //Write your code here 
}  
shortestLongest(["hi", "cat", "hello"]) -> ["hi", "hello"] 
shortestLongest(["lol", "cuttie", "kitty"]) -> ["lol", "cuttie"]
```
6.Write a function called minMax that takes an array as a parameter and returns a new array with the smallest and largest number.
```js

function minMax(array) {
   //Write your code here 
}  
minMax([1, 5, 4, 3]) -> [1, 5] 
minMax([1, 5, -1, 3]) -> [5, -1]  
```
7.Write a function called multiplyBy that takes an array and number as parameters and returns a new array with each of the elements from the array multiplied by the given number.
```js

function multiplyBy(array, number) {
   //Write your code here 
}  
multiplyBy([1, 5, 4, 3], 2) -> [2, 10, 8, 6]   
multiplyBy([1, 6, 2, 3], 1) -> [1, 6, 2, 3]
```
8.Write a function called multiplyByIndex that takes an array as a parameter, and multiplies each element with their corresponding index values then returns that array.
```js

function multiplyByIndex(array) {
   //Write your code here 
}  
multiplyByIndex([1, 5, 4, 3]) -> [0, 5, 8, 9]   
multiplyByIndex([5, 10, 15]) -> [0, 10, 30]  
```
9.Write a function called lengths that takes an array of strings as a parameter, and returns an array of numbers representing the length of each string.
```js

function lengths(array) {
   //Write your code here 
}  
lengths(["hi", "cat", "hello"]) -> [2, 3, 5]     
lengths(["lol", "cuttie"]) -> [3, 6] 
```
10.Write a function called totalNumberOfCharacter that takes an array of strings as a parameter, and returns the total number of characters of all the strings in the array.
```js

function totalNumberOfCharacters(array) {
   //Write your code here 
}  
totalNumberOfCharacters(["hi", "cat", "hello"]) -> 10    
totalNumberOfCharacters(["", "cuttie"]) -> 6  
```
## Advanced
1.Write a function called filterEvenLengthWords that takes an array of strings as a parameter, and returns an array containing only the elements of the given array whose length is an even number.
```js

function filterEvenLengthWords(array) {
   //Write your code here 
}  
filterEvenLengthWords(["hi", "cat", "hello"]) -> ["hi"]   
filterEvenLengthWords(["", "cuttie", “cat”]) ->  [“”, "cuttie"] 
```
2.Write a function called popLastElement that takes an array of arrays as a parameter, and removes the last element from every array in the array, and returns the array.
```js

function popLastElement(array) {
   //Write your code here 
}  
popLastElement([[1 , 2, 3, 4], [1, 2], [3, 4, 5]]) ->  [[1, 2, 3], [1], [3, 4]] 
popLastElement([[1, 0, 3], [1], [3, 10]]) ->  [[1, 0], [3]]  
```
3.Write a function called pushLastElement that takes an array of arrays and element as a parameter, and adds the element to the end of every array in the array, and returns the array.
```js

function pushLastElement(array, element) {
   //Write your code here 
}  
pushLastElement ([[2, 3], [2], [3, 4]], 1) ->  [[2, 3, 1], [2, 1],[3, 4, 1]] 
pushLastElement ([[1], [1, 2]], 0) -> [[1, 0], [1, 2, 0]]
```
4.Write a function called sumArrays that takes an array of arrays as a parameter, and returns the sum of all elements in the arrays.

function sumArrays(array) {
   //Write your code here 
}  
```js

sumArrays ([[1, 2, 3, 4],[1, 2],[3, 4, 5]]) -> 25 
sumArrays ([[1, 0, 3], [1], [3, 10]]) -> 18   
```
5.Write a function called multiplyBySmallest that takes an array as a parameter, and returns a new array with each of the elements from the array multiplied by the smallest number in the array.
```js

function multiplyBySmallest(array) {
   //Write your code here 
}  
multiplyBySmallest([2, 3, 4]) -> [4, 6, 8] 
multiplyBySmallest([0, 1, 4]) -> [0, 0, 0]  
```

6.Write a function called joinArrays that takes an array of arrays as parameters, and returns a single array containing all the elements of the nested arrays.
```js

function joinArrays(array) {
   //Write your code here 
}  
joinArrays ([[2, 3], [2], [3, 4]]) -> [2, 3, 2, 3, 4] 
joinArrays ([[1], [1, 2]]) -> [1, 1, 2]   
```
7.Write a function called sumOddEven that takes an array as a parameter, and returns an array containing the sum of the odd numbers as the first element and the sum of the even numbers as the second element.
```js

function sumOddEven(array) {
   //Write your code here 
}  
sumOddEven ([1, 3, 2, 4]) -> [4, 6] 
sumOddEven ([0, 1, 4]) -> [1, 4] 
```
7.Write a function called shortestOfMixed that takes an array of mixed elements as a parameter, and returns the shortest string within the given array.
```js

function sumOddEven(array) {
   //Write your code here 
}  
sumOddEven ([1, 3, 2, 4]) -> [4, 6] 
sumOddEven ([0, 1, 4]) -> [1, 4] 
```
Notes: If there are ties, it should return the first element to appear in the given array. Expect the given array to have values other than strings. If the given array is empty, it should return an empty string. If the given array contains no strings, it should return an empty string.


8.Write a function called smallestOfMixed that takes an array an array of mixed elements as a parameter, and returns the smallest number within the given array. Notes: If the given array is empty, it should return 0. If the array contains no numbers, it should return 0.
```js

function smallestOfMixed(array) {   //Write your code here }  smallestOfMixed ([4, "two", 2, "three"]) -> 2 smallestOfMixed (["too", "two", "three"]) -> 0   
```