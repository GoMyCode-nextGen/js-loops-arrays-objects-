# Repetition with functions 
Exercises
## Basic Requirements
1.Write a function called sum that takes a number as a parameter and returns the sum of all integers up to the given number starting from 0.
```js
function sum(number) {
   //Write your code here 
}  
sum(3) -> 6 
sum(4) -> 10 
sum(5) -> 15
```
2.Write a function called factorial that takes a number as a parameter and returns the factorial of the given number. The factorial is the product of all the integers before a given number, starting with 1. The factorial of 0 is 1.
```js
function factorial(number) {
   //Write your code here 
}  
factorial(3) -> 6 
factorial(4) -> 24 
factorial(5) -> 120
```
3.Write a function called repeatString that takes two parameters, a string and a number and returns a new string with the given string repeated the given number of times.
```js
function repeatString(string, number) {
   //Write your code here 
}  
repeatString(‘dog’, 0) -> ‘’ 
repeatString(‘dog’, 1) -> ‘dog’ 
repeatString(‘dog’, 2) -> ‘dogdog’ 
repeatString(‘dog’, 3) -> ‘dogdogdog’
```
4.Write a function called fibonacci that takes a number as a parameter and returns the nth term in the fibonacci sequence. The fibonacci sequence is: 0 1 1 2 3 5 8 13 21 .. Every number in the sequence is the sum of the previous two numbers: 5 = 2 + 3, 8 = 3 + 5, etc. The first two numbers are the exception and are equal to 1. You can use this link for more information about Fibonacci https://www.omnicalculator.com/math/fibonacci
```js
function fibonacci(number) {
   //Write your code here 
}  
fibonacci(5) -> 5 
fibonacci(6) -> 8 
fibonacci(7) -> 13
```
5.Write a function called multiplyBy10 that takes two numbers as parameters and returns the first number multiplied by 10 the amount of times specified by the second number.
```js
function multiplyBy10(firstNumber, secondNumber) {
   //Write your code here 
}  
multiplyBy10(4, 3) -> 4000 
multiplyBy10(5, 2) -> 500
```
## More Practice
1.Write a function called sumBetween that takes two numbers (start and end) as parameters and returns the sum of the numbers from start to end. What happens if the start is larger than the end? Modify the function to check for this case and, when found, swap the start and end.
```js
function sumBetween(start, end) {
   //Write your code here 
}  
sumBetween(2, 7) -> 27  
sumBetween(2, 5) -> 14  
sumBetween(5, 2) -> 14 
```
2.Write a function called add that takes two numbers as parameters and returns their sum. You can only use inc and dec to accomplish this.
```js
function add(number1, number2) {
   //Write your code here 
}  function inc(x) {
   return x + 1 
}  function dec(x) {
   return x - 1 
}  
add(1, 2) -> 3 
add(2, 2) -> 4 
add(5, 5) -> 10
```
3.Write a function called isEven that takes a number as parameter and returns true if that number is even, and false otherwise; You can not use the modulus % operator
```js
function isEven(number) {
   //Write your code here 
}  
isEven(3) -> false 
isEven(2) -> true
```
4.Write a function called range that takes two numbers as parameters and returns an array of all the integers between the two numbers, excluding both numbers.
```js
function range(start, end) {
   //Write your code here 
}  
range(1,9) -> ”2, 3, 4, 5, 6, 7, 8”  
range(21, 25) -> ”21, 23, 24” 
```
Read about Increment and Decrement operators in JS

5.Write a function called multiply that takes two numbers as parameters and returns their multiplication You can not use the multiplication * operator, you must use repeated addition.
```js
function multiply(number1, number2) {
   //Write your code here 
} 
 multiply(3, 2) -> 6 
multiply(5, 5) -> 25
```
HINT: Think about using increment and decrement operators.
## Advanced
1.Write a function called stringLength that takes a string as a parameter and returns the length of that string. You cannot use the length property of the string. Instead, you'll need to use the string method called .slice().
```js
function stringLength(string) {
   //Write your code here 
}  
stringLength(‘hello’) -> 5 
stringLength(‘hi’) -> 2
```
2.Write a function called modulo that takes two numbers as parameters and returns the remainder after dividing the first number by the second number. You cannot use the % operator to solve this question.
```js
function modulo(number1, number2) {
   //Write your code here 
}  
modulo(5, 2) -> 1 
modulo(6, 3) -> 0 
modulo(8, 10) -> 8
```
3.Write a function called countChars that takes two parameters a string and a character and returns a number representing the number of times that the character appears in the string. Use the .slice() method.
```js
function countChars(string, char) {
   //Write your code here 
}  
countChars(“Hi”,“i”) -> 1 
countChars(“Hello”,“l”) -> 2 
countChars(“Hello”,“x”) -> 0
```
4.Write a function called indexOf that takes two parameters, a string and a character and returns the index of the first occurance of the character in the string.
```js
function indexOf(string, char) {
   //Write your code here 
}  
indexOf(“Hello”,“l”) -> 2 
indexOf(“Hi”,“i”) -> 1 
indexOf(“Hi”,“x”) -> undefined
```
5.Write a function called power that takes two numbers (base & exponent) as parameters and returns the result of raising the base to the exponent. The power function in the lecture works but can be made considerably faster through a method known as successive squaring. To get an idea of how this works, observe that: 24 = (22)2 27 = 2(23)2 28 = (24)2 Modify the power function to take advantage of this technique.
```js
function power(base, exponent) {
   //Write your code here 
}  
power(2, 3) -> 8 
power(3, 4) -> 81 
power(2, 0) -> 1
```
6.Write a function called reverseString that takes a string as a parameter and returns the reverse of the string.
```js
function reverseString(string) {
   //Write your code here 
}  
reverseString(“Fatima”) -> “amitaF” 
reverseString(“Hello World”) -> “dlroW olleH”
```
7.Write a function called greatestCommonDivisor that takes two numbers as parameters and returns the greatest common divisor.
```js
function greatestCommonDivisor(number1, number2) {
   //Write your code here 
}  
greatestCommonDivisor(50, 120) -> 10 
greatestCommonDivisor(24, 54) -> 6
```
8.Write a function called lowestCommonMultiple that takes two numbers as parameters and returns lowest common multiple Note: Assume that the two numbers are greater than or equal to 2.
```js
function lowestCommonMultiple(number1, number2) { 
  //Write your code here 
}   
lowestCommonMultiple(4, 6) -> 12 
lowestCommonMultiple(15, 2) -> 60
```
9.Write a function called numberOfHandshakes that takes a number of people in a party as a parameter and returns the total number of unique handshakes. Every person can only handshake every other person once.
```js
function numberOfHandshakes(n) {
   //Write your code here 
}  
numberOfHandshakes(2) -> 1 
numberOfHandshakes(3) -> 3 
numberOfHandshakes(4) -> 6 
numberOfHandshakes(5) -> 10
```