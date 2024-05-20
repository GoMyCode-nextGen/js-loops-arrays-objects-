Exercises
Basic Requirments
1.Write a function called sumOfN that takes a number as a parameter and returns the sum of that number and all the numbers before it.
```js
function sumOfN(n) {
   //Write your code here 
}  
sumOfN(5) -> 15 
sumOfN(3) -> 6
```
2.Write a function called factorialOfN that takes a whole number as a parameter and returns the factorial of that number.
```js
function factorialOfN(n) {
   //Write your code here 
}  
factorialOfN(5) -> 120 
factorialOfN(3) -> 6 
factorialOfN(1) -> 1 
factorialOfN(0) -> 1
```
3.Write a function called repeatString that takes two parameters, as string and a number, and returns that string the number of times specified in the second parameter.
```js
function repeatString(string, num) {
   //Write your code here 
}  
repeatString(“Hi”, 5) -> “HiHiHiHiHi” 
repeatString(“dog”, 3) -> “dogdogdog”
```
4.Write a function called countMinMax that takes two numbers as parameters and returns the range.
```js
function countMinMax(min, max) {
   //Write your code here 
}  
countMinMax(10, 15) -> 5 
countMinMax(0, 3) -> 3
```
5.Write a function called sumMinToMax that takes two numbers as parameters and returns the sum between the two integers beginning at the num1 and excluding num2.
```js
function sumMinToMax(min, max) {
   //Write your code here 
}  
sumMinToMax(1, 5) -> 10 
sumMinToMax(3, 7) -> 18
```
6.Write a function called productMinToMax that takes two numbers as parameters and returns the product between the two integers beginning at the num1 and excluding num2.
```js
function productMinToMax(min, max) {
   //Write your code here 
}  
sumMinToMax(1, 5) -> 24 
sumMinToMax(3, 7) -> 360
```
7.Write a function called multiplyBy10NTimes that takes two numbers as parameters and returns the first number multiplied by 10 the amount of times indicated by the second number.
```js
function multiplyBy10NTimes(num, n) {
   //Write your code here 
}  
multiplyBy10NTimes(3, 3) -> 3000 
multiplyBy10NTimes(5, 2) -> 500
```
8.Write a function called countCharAtIndex that takes three parameters, a string, an index, and another string. This function should use the index to find the corresponding character in the first string and loop through the second string and count how many times that character occurs.
```js
function countCharAtIndex(string1, index, string2) {
   //Write your code here 
}  
countCharAtIndex(“hello”, 2, “lol”) -> 2 
countCharAtIndex(“world”, 3, “Hello World”) -> 3
```
More Practice
1.Write a function called reverseString that takes a string as an input and returns that string in reverse.
```js
function reverseString(string) {
   //Write your code here 
}  
reverseString(“hello”) -> “olleh” 
reverseString(“world”) -> “dlrow”
```
2.Write a function called getIndexOf that takes two parameters, a string, and a character, and returns the first position of the character in that string.
```js
function getIndexOf(string, char) {
   //Write your code here 
}  
getIndexOf(“I am a hacker”, “a”) -> 2 
getIndexOf(“hello”, “h”) -> 0
```
Advanced
1.Write a function called sumEven that takes two numbers as parameters and returns the sum of all even numbers starting from num1 and excluding num2.
```js
function sumEven(number1, number2) {
   //Write your code here 
}  
sumEven(3, 9) -> 18 
sumEven(1, 6) -> 6
```
2.Write a function called primeCounter that takes a number as a parameter and returns the amount of prime numbers that occur before it.
```js
function primeCounter(number) {
   //Write your code here 
}  
primeCounter(10) -> 4 
primeCounter(7) -> 3
```

3.Write a function called sumOfFirstAndLast that takes a number as a parameter and returns the sum of the first and last digits. Please do this without turning the number into a string.
```js
function sumOfFirstAndLast(number) {
   //Write your code here 
}  
sumOfFirstAndLast(892) -> 10 
sumOfFirstAndLast(20003) -> 5
```