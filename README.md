# Arrays 
Exercises
## Basic Requirments
1.Declare a variable, call it myArray, and assign it to an array that contains three elements.
2.Refer to the following array for the next three questions: [‘dog’, ‘cat’, ‘fox’, ‘monkey’].

What is the index of ‘dog’? 
b-What is the index of ‘fox’? 
c-What is the index of ‘monkey’?


3.Fix the typos in the following arrays, make it one correct array
```js

[1, 2 3 4 5, 6, 7]  ‘The’ ‘quick’ ‘brown’, ‘fox’ ‘jumped’, ‘over’ the lazy, ‘dog, ]  true false, true]

```

4.Write a function called emptyArray that takes no parameters and returns an empty array.
```js
function emptyArray() {
   //Write your code here 
}  
emptyArray() -> []
```
5. Write a function called numbersArray that takes no parameters and returns an array of numbers from 1 to 5.
```js
function numbersArray() {
   //Write your code here 
}  
numbersArray() -> [1, 2, 3, 4, 5]
```
6.Write a function called booleansArray that takes no parameters and returns an array of three true booleans
```js
function booleansArray() {
   //Write your code here 
}  
booleansArray() -> [true, true, true]
```
7.Write a function called stringsArray that takes no parameters and returns an array of two strings, your first name and last name.
```js
function stringsArray() {
   //Write your code here 
}  
stringsArray() -> [‘Ahmed’, ‘Vega’]
```
8.Write a function called arrayLength that takes an array as a parameter and returns the length of that array.
```js
function arrayLength(array) {
   //Write your code here 
}  
arrayLength([1, 2, 3, 4]) -> 4 
arrayLength([]) -> 0
```
## More Practice
1.Write a function called firstElement that takes an array as a parameter and returns the first element in that array.
```js
function firstElement(array) {
   //Write your code here 
}  
firstElement([1, 2, 3, 4]) -> 1 
firstElement([3, 4, 5]) -> 3
```
2.Write a function called lastElement that takes an array as a parameter and returns the last element from that array.
```js
function lastElement(array) {
   //Write your code here 
}  
lastElement([1, 2, 3, 4]) -> 4 
lastElement([1, 2, 3]) -> 3

```
3.Write a function called getNthElement that takes two parameters, an array and a number, and returns the element in the spot indicated by the number. NOTE: (Remember that index starts at 0).
```js
function getNthElement(array, number) {
   //Write your code here 
}  
getNthElement([1, 2, 3, 4, 5], 3) -> 4 
getNthElement([1, 2, 3, 4, 5], 1) -> 2
```
4.Write a function called push that takes two parameters, an array and a new element, and returns a new array with the element added to the end.
```js
function push(array, element) {
   //Write your code here 
}  
push([‘cat’, ‘dog’, ‘fox’], ‘monkey’) ->  [‘cat’, ‘dog’, ‘fox’, ‘monkey’] 
push([camel, ‘goat’], ‘sheep’) ->  [‘camel’, ‘dog’, ‘sheep’]
```
5.Write a function called pop that takes an array as a parameter and returns a new array with the last element removed from it.
```js
function pop(array) {
   //Write your code here 
}  
pop ([‘cat’, ‘dog’, ‘fox’] -> [‘cat’, ‘dog’] 
pop ([‘cat’, ‘dog’] -> [‘cat’]
```
6.Write a function called unshift that takes two parameters, an array and an element, and returns a new array with the element added to the front.
```js
function unshift(array, element) {
   //Write your code here 
}  
unshift ([‘cat’, ‘dog’, ‘fox’], ‘monkey’) -> [‘monkey’, ’cat’, ‘dog’, ’fox’] 
unshift ([‘cat’, ‘dog’], ‘fox’) -> [‘fox’, ’cat’, ‘dog’]
```
7.Write a function called shift that takes an array as a parameter and returns a new array with the first element removed.
```js
function shift(array) {
   //Write your code here 
}  
shift ([‘cat’, ‘dog’, ‘fox’]) -> [‘dog’, ‘fox’] 
shift ([‘cat’, ‘dog’]) -> [‘dog’]
```
8.Write a function called reassignLast that takes two parameters, an array, and an element, and returns a new array with the last element of the original array replaced with the new element.
```js
function reassignLast(array, element) {
   //Write your code here 
}  
reassignLast([‘cat’, ‘dog’, ‘fox’], ‘monkey’) -> [‘cat’, ‘dog’, ‘monkey’] 
reassignLast ([‘cat’, ‘dog’], ’camel’) ->           [‘cat’, ‘camel’]
```
9.Write a function called reassignNthElement that takes three parameters, an array, a numerical index and a new value, and returns a new array with the new value in the place of the element at the specified index.
```js
function reassignNthElement(array, index, element) {
   //Write your code here 
}  
reassignNthElement([‘cat’, ‘dog’, ‘fox’], 0, ‘monkey’) -> [‘monkey’, ‘dog’, ‘fox’] 
reassignNthElement([‘cat’, ‘dog’], 2, ‘camel’) ->           [‘cat’, ‘dog’,’camel’]
```
## Advanced
1.Write a function called indexOf that takes two parameters, an array, and an element, and returns the index of the array where the element is located.
```js
function indexOf(array, element) {
   //Write your code here 
}  
indexOf([‘cat’, ‘dog’, ‘fox’], ‘fox’) ->  2 
indexOf([‘cat’, ‘dog’, ‘fox’], ‘cat’) ->  0
```
3.Write a function called addElement that takes three parameters, an array, an index and an element, and returns an array with that element added in the place of that index but nothing in the array is removed. NOTE: Please use this exercise to practice .splice()
```js
function addElement(array, index, element) {
   //Write your code here 
}  
addElement( [‘cat’, ‘dog’, ‘fox’], 1, ‘monkey’) ->  [‘cat’, ‘monkey’, ‘dog’, ‘fox’] 
addElement( [‘camel’,’cat’,’kitty’], 2, ‘doggy’) ->  [‘camel’, ‘cat’, ‘doggy’, ‘kitty’]
```
3.Write a function called removeElement that takes two parameters, an array and an index, and returns an array with the element in that index removed. NOTE: Please use this exercise to practice .splice()
```js
function removeElement(array, index) {
   //Write your code here 
}  
removeElement( [‘cat’, ‘monkey’, ‘dog’, ‘fox’], 2) ->  [‘cat’, ‘monkey’, ‘fox’] 
addElement( [‘camel’,’cat’,’kitty’], 1) ->   [‘camel’, ‘kitty’]
```
4.Write a function called concatArrays that takes two parameters, two arrays, and returns a new array that combines all elements of the two parameters
```js
function concatArrays(array, array) {
   //Write your code here 
}  
concatArrays( [‘cat’, ‘dog’, ‘fox’], [‘doggy’, ‘kitty’]) -> [‘cat’, ‘dog’, ‘fox’, ‘doggy’, ‘kitty’] 
concatArrays( [1, 2, 3, 4, 5], [6, 7, 8, 9] ) ->   [1, 2, 3, 4, 5, 6, 7, 8, 9]
```
4.Write a function called concatThreeArrays that takes three parameters, three arrays, and returns a new array that combines all elements of the two parameters
```js
function concatThreeArrays(array,array,array) {
   //Write your code here 
}  
concatThreeArrays( [‘cat’, ‘dog’, ‘fox’], [‘doggy’, ‘kitty’], [‘camel’, ‘bird, ‘goat’]) ->  [‘cat’, ‘dog’, ‘fox’, ‘doggy’, ‘kitty’, ‘camel’, ‘bird, ‘goat’] 
concatThreeArrays( [1, 2, 3, 4, 5], [6, 7, 8, 9], [10, 11] ) ->   [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11]
```
5.Write a function called joinStrings that takes two parameters, an array of strings and one string, and returns a new string that combines all of the strings from the array separated by the string parameter. NOTE: Use .join()
```js
function concatThreeArrays(array,array,array) {
   //Write your code here 
}  
concatThreeArrays( [‘cat’, ‘dog’, ‘fox’], [‘doggy’, ‘kitty’], [‘camel’, ‘bird, ‘goat’]) ->  [‘cat’, ‘dog’, ‘fox’, ‘doggy’, ‘kitty’, ‘camel’, ‘bird, ‘goat’] 
concatThreeArrays( [1, 2, 3, 4, 5], [6, 7, 8, 9], [10, 11] ) ->   [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11]
```
6.Write a function called joinStrings that takes two parameters, an array of strings and one string, and returns a new string that combines all of the strings from the array separated by the string parameter. NOTE: Use .join()
```js
function joinStrings(array, string) {
   //Write your code here 
}  
joinStrings( [‘cat’, ‘monkey’, ‘dog’, ‘fox’], ‘-’) ->  ‘cat-monkey-dog-fox’ 
joinStrings( [‘hello’,’beautiful’,’world’], ‘ ‘) ->   ‘hello beautiful world’
```
7.Write a function called applySplit that takes two parameters, a string to be split and a splitter (which is also a string), and returns an array that is the result of splitting the string on the splitter. NOTE: Use .split()
```js
function applySplit(string, splitter) {
   //Write your code here 
}  
applySplit( ‘one-two-three’, ‘-’) ->  [‘one’, ‘two’, ‘three’] 
applySplit( ‘hello beautiful world’, ‘ ‘) ->   [‘hello’, ‘beautiful’, ‘world’]
```
8.Write a function called getElementsAfter that takes two parameters, an array and index, and returns an array with all the elements after the index but does not include the element at the given index.
```js
function getElementsAfter(array, index) {
   //Write your code here 
}  
getElementsAfter( [‘cat’, ‘monkey’, ‘dog’, ‘fox’], 1) ->  [‘dog’, ‘fox’] 
getElementsAfter( [‘camel’,’cat’,’kitty’], 0) ->   [‘cat’, ‘kitty’]
```
9.Write a function called getElementsBefore that takes two parameters, an array and index, and returns an array with all the elements before the index but does not include the element at the given index.
```js
function getElementsBefore(array, index) {
   //Write your code here 
}  
getElementsBefore( [‘cat’, ‘monkey’, ‘dog’, ‘fox’], 2) ->  [‘cat’, ‘monkey’] 
getElementsBefore( [‘camel’,’cat’,’kitty’], 1) ->   [‘camel’]
```
10.Write a function called getElementsBefore that takes two parameters, an array and index, and returns an array with all the elements before the index but does not include the element at the given index.
```js
function getAllElementsButFirst(array) {
   //Write your code here 
}  
getAllElementsButFirst([‘cat’, ‘monkey’, ‘dog’, ‘fox’]) ->  [‘monkey’, ‘dog’, ‘fox’] 
getAllElementsButFirst( [‘camel’,’cat’,’kitty’]) ->   [’cat’,’kitty’]
```
11.Write a function called getAllElementsButLast that takes an array as a parameter and returns an array with all the elements but the last element.
```js
  function getAllElementsButLast(array) {
   //Write your code here 
}  
getAllElementsButLast([‘cat’, ‘monkey’, ‘dog’, ‘fox’]) ->  [‘cat’, ‘monkey’, ‘dog’] 
getAllElementsButLast([‘camel’,’cat’,’kitty’]) ->   [‘camel’, ‘cat’]
```