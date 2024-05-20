# Objects 
## Basic Requirements
1.Fix the syntax & style issues with the three objects below:
```js
 {firstName 'Yan', lastname: 'Fan' } 
 {a: 1, b:2 c: 3 d 4} 
 { 
       animal: 'dog' 
       noise: 'bark', 
       age: 3, 
       type 'Golden Retriever' 
       color: 'Yellow', 
 }
 ```
2. Create an object that represents you. It should contain your first name, last name, age and hometown. Assign it to a variable called person.

3.Access the favorite food property in the object using dot notation, and reassign it to a different food.

4.Change your object to have a single name key, the value of which is an object – this object should have first, last and middle keys containing your first, last, and middle names respectively.

5.Write a function called emptyObject that takes no parameters and returns an empty object.
```js
function emptyObject(){  
  //Write your code here 
}  
emptyObject() -> {}
```
6.Write a function called addProperty that takes two parameters, an object, and a key as a string. It then adds the key as a property in the object and gives it the value true.
```js
function addProperty(object, key) {   
 //Write your code here
 }  
var‌ ‌‌myObject‌ ‌‌=‌‌ ‌{‌ ‌        ‌animal:‌ ‌‘cat’‌, ‌        ‌food:‌ ‌‘turkey’‌, ‌        ‌age:‌ ‌‌3‌ ‌ } 
 console.log‌(myObject.kittens) -> ‌undefined addProperty‌(myObject,‌ ‌‘kittens’)‌‌ ‌
 console.log‌(myObject.kittens) -> ‌true‌ 
 ```
7.Write‌ ‌a‌ ‌function‌ ‌called‌ ‌‌deleteProperty‌‌ ‌that‌ ‌takes‌ ‌takes two parameters an‌ ‌object‌ ‌and‌ a key as a string. It then removes the property with that key from the object.
```js
‌function‌‌ ‌‌deleteProperty‌(‌object,‌ ‌key‌)‌ ‌{‌ ‌ 
  ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌ 
}‌ ‌  
var‌‌ ‌‌myObject‌ ‌‌=‌‌ ‌{‌ ‌        ‌animal:‌ ‌‘cat’‌, ‌        ‌food:‌ ‌‘turkey’, ‌        ‌age:‌ ‌‌3‌ ‌ }
console.log‌(myObject.age) ‌‌-> ‌3 deleteProperty‌(myObject,‌ ‌‘age’)‌‌
console.log‌(myObject.age) ‌‌-> ‌undefined‌ ‌
```
8.Write‌ ‌a‌ ‌function‌ ‌called‌ ‌‌addObjectProperty‌‌ ‌that‌ ‌takes‌ ‌three‌ ‌parameters,‌ ‌an‌ ‌object,‌ ‌a‌ ‌string as a key‌, ‌and‌ ‌a second ‌object. It then adds a new property with the passed key and the second object as its value.
```js
‌function‌‌ ‌‌addObjectProperty‌(‌object1,‌ ‌key,‌ ‌object2‌)‌ ‌{‌ ‌   ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌ }‌ ‌  var‌‌ ‌‌person1‌ ‌‌=‌‌ ‌{‌ ‌    ‌name:‌ ‌‌'Ahmad'‌,‌ ‌    ‌role:‌ ‌‌'worker'‌ ‌ }   var‌‌ ‌‌person2‌ ‌‌=‌‌ ‌{‌ ‌    ‌name:‌ ‌‌'Fadi'‌,‌ ‌    ‌role:‌ ‌‌'supervisor'‌ ‌ } ‌  console.log‌(person1.manager) ‌‌-> undefined addObjectProperty‌(person1,‌ ‌‌‘manager’‌,‌ ‌person2)  ‌console.log‌(person1.manager) ‌‌-> {name: ’Fadi’,‌ role: ’manager’}‌ ‌
```
9.Write‌ ‌a‌ ‌function‌ ‌called‌ ‌‌addFullNameProperty‌‌ ‌that‌ ‌takes‌ ‌an‌ ‌object‌ ‌as‌ ‌a‌ ‌parameter.‌ ‌If the object has both a firstName and a lastName property, then it adds a new property with the key fullName and the value as a string of the firstName and lastName combined with a space between them.
```js
‌function‌‌ ‌‌addFullNameProperty‌(‌object‌)‌ ‌{‌ ‌ 
  ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌ 
}‌ ‌ 
var‌‌ ‌‌person‌ ‌‌=‌‌ ‌{‌ ‌   ‌firstName:‌ ‌‌'Leena'‌,‌ ‌   ‌lastName:‌ ‌‌'Atia'‌ ‌ }
console.log‌(person.fullName) ‌‌-> undefined ‌ 
addFullNameProperty‌(person) ‌ 
console.log‌(person.fullName) ‌‌-> ‌‘Leena‌ ‌Atia’‌ 
```
10.Write‌ ‌a‌ ‌function‌ ‌called‌ ‌‌addArrayProperty‌‌ ‌that‌ ‌takes‌ ‌three‌ ‌parameters,‌ ‌an‌ ‌object,‌ ‌a‌ ‌string as a key‌ ‌and‌ ‌an‌ ‌array.‌ ‌It then adds a new property to the object with the specified key and its value is the array.
```js
function‌‌ ‌‌addArrayProperty‌(‌object,‌ ‌key,‌ ‌array‌)‌ ‌{‌
   ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌ 
}‌
var‌‌ ‌‌myObject‌ ‌‌=‌‌ ‌{} ‌ 
var‌‌ ‌‌myArray‌ ‌‌=‌‌ ‌[‌1‌,‌ ‌‌3‌] 
console.log‌(myObject.myProperty) ‌-> ‌undefined 
addArrayProperty‌(myObject, ’myProperty’‌‌, myArray);‌
console.log‌(myObject.myProperty) ‌-> ‌[1,3]‌ ‌‌‌
```
11.Write‌ ‌a‌ ‌function‌ ‌called‌ ‌‌printAllProperties‌‌ ‌that‌ takes ‌an‌ ‌object‌ ‌as a parameter. It then prints out to the console the values of all the object’s properties.
```js
‌function‌‌ ‌‌printAllProperties‌(‌object)‌ ‌{‌ ‌ 
  ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌
}‌ ‌  
var‌‌ ‌‌person‌ ‌‌=‌‌ ‌{‌ ‌   ‌firstName:‌ ‌‌'Leena'‌,‌ ‌   ‌lastName:‌ ‌‌'Atia'‌ ‌ }
printAllProperties‌(person);‌ -> ‘Leena’     ‘Atia’‌
NOTE: Use‌ ‌this‌ ‌to‌ ‌practice‌ ‌(for...in‌) ‌statements‌‌‌.
```
More Practice
1.Write a function called removeNumbersLargerThan that takes two parameters, a number and an object. It then removes all properties with values larger than the specified number.
```js
‌‌‌‌function‌‌ ‌‌removeNumbersLargerThan‌(‌number, object‌)‌ ‌{‌ ‌ 
  ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌ 
}‌ ‌  
 var‌‌ ‌‌obj‌ ‌‌=‌‌ ‌{‌ ‌   ‌a:‌ ‌‌8‌,‌ ‌   ‌b:‌ ‌‌2‌,‌ ‌   ‌c: ’montana’‌ ‌ }
 console.log‌(obj) -> ‌‌{‌ ‌a: 8, b:‌ ‌2,‌ ‌c:‌ ‌’montana’ ‌}‌ 
 removeNumbersLargerThan‌(‌5‌,‌ ‌obj) 
 console.log‌(obj) -> ‌‌{‌ ‌b:‌ ‌2,‌ ‌c:‌ ‌’montana’ ‌}‌ 
 ```
2.Write a function called removeAllEvenValues that takes an object as a parameter. It then removes all properties with values that are an even number.
```js
function‌‌ ‌‌removeAllEvenValues(‌object‌)‌ ‌{‌ ‌
   ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌
 }‌ ‌
  var‌‌ ‌‌obj‌ ‌‌=‌‌ ‌{‌ ‌   ‌a:‌ ‌‌9,‌ ‌   ‌b:‌ ‌‌2‌,‌ ‌   ‌c: ’montana’‌ ‌ } 
 console.log‌(obj) -> ‌‌{‌ ‌a:‌ ‌9,‌ b: 2, ‌c:‌ ‌'montana'‌ ‌}‌  ‌
 removeAllEvenValues(‌obj) 
 console.log‌(obj) -> ‌‌{‌ ‌a:‌ ‌9,‌ ‌c:‌ ‌'montana'‌ ‌}‌ ‌ 
 ```
3.Write a function called removePropertiesNotEqualTo10 that takes an object as a parameter. It then removes all properties that are not equal to 10.
```js

‌‌‌‌function‌‌ ‌‌removePropertiesNotEqualTo10(‌object‌)‌ ‌{‌ ‌ 
  ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌
 ‌}‌ ‌  
var‌‌ ‌‌obj‌ ‌‌=‌‌ ‌{‌ ‌   ‌a:‌ ‌‌10,‌   ‌b:‌ ‌‌2‌,‌ ‌   ‌c: ’montana’‌,   d: 10,   e: ’ohio’,   f: 10 ‌ } 
removePropertiesNotEqualTo10(‌obj) ‌ 
console.log‌(obj) -> ‌‌{ a: 10, d: 10, f: 10 } 
```js
4.Write a function called removeStringsLongerThan that takes two parameters, a number and an object. It then removes all strings with lengths larger than the number parameter.
```js
‌‌‌‌function‌‌ ‌‌removeStringsLongerThan(‌object‌, number)‌ ‌{‌ ‌ 
  ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌ 
}‌
 ‌var‌‌ ‌‌obj‌ ‌‌=‌‌ ‌{‌ ‌   ‌a:‌ ‌‌’Texas’,‌   ‌b:‌ ‌‌2‌,‌ ‌   ‌c: ’montana’‌ }  ‌
 removeStringsLongerThan(‌6, obj) 
 console.log‌(obj) ‌-> ‌‌{ a: ‘Texas’, b: 2 } 
 ```
5.Write a function called removeAllNumbers that takes an object as a parameter. It then removes all properties in the object that have number values.
```js
‌‌‌‌function‌‌ ‌‌removeAllNumbers(‌object‌)‌ ‌{‌ ‌
   ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌ 
}‌ ‌ 
 var‌‌ ‌‌obj‌ ‌‌=‌‌ ‌{‌ ‌   ‌a:‌ ‌‌9,‌   ‌b:‌ ‌‌2‌,‌ ‌   ‌c: ’montana’‌ }  ‌
 removeAllNumbers(‌obj) ‌
 console.log‌(obj) ‌‌-> ‌‌{ c: ‘montana’ } 
 ```
6.Write a function called removeArrays that takes an object as a parameter. It then removes all properties that have array values.
```js
‌‌‌‌function‌‌ ‌‌removeArrays(‌object‌)‌ ‌{‌ ‌
   ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌
 }‌ ‌ 
var‌‌ ‌‌obj‌ ‌‌=‌‌ ‌{‌ ‌   ‌a:‌ [1, 3, 4],‌   ‌b:‌ ‌‌2‌,‌ ‌   ‌c:[‘hi’,’there’‌] }  ‌
removeArrays(‌obj) 
console.log‌(obj) ‌‌-> ‌‌{ b: 2 } 
```
7.Write a function called getFirstElementOfProperty that takes an object and a key and returns the first element in the array at the given key. If the array is empty it should return undefined. If the property at the given key is not an array it should return undefined. If there is no property at the key it should return undefined.
```js
‌‌‌‌function‌‌ ‌‌getFirstElementOfProperty(‌object‌, key)‌ ‌{‌ ‌ 
  ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌ 
}‌ ‌
var‌‌ ‌‌obj‌ ‌‌=‌‌ ‌{‌ ‌   array:‌ [1, 2, 4] }
getFirstElementOfProperty(obj, ‘array’) -> 1
```
8.Write a function called getNthElementOfProperty that takes three parameters, an object, a key and a number. It then returns the element located at the index equal to the number parameter from the array at the given key. If the array is empty it should return undefined. If the property at the given key is not an array it should return undefined. If there is no property at the key it should return undefined.
```js
‌‌‌‌function‌‌ ‌‌getNthElementOfProperty(‌object‌, key, number)‌ ‌{‌ ‌ 
  ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌
}‌ ‌
var‌‌ ‌‌obj‌ ‌‌=‌‌ ‌{‌ ‌   ‌array:‌ [1, 2, 6] } 
getNthElementOfProperty(obj, ‘array’, 1) -> 2 
getNthElementOfProperty(obj, ‘array’, 2) -> 6
```
## Advanced

1.Write a function called isPropertyPresent that takes two parameters, an object and a key. It then returns true if there is a property at the given key and false otherwise.
```js
function‌‌ ‌‌isPropertyPresent(‌object‌, key)‌ ‌{‌
 ‌   ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌
 }‌ ‌ 
var‌‌ ‌‌obj‌ ‌‌=‌‌ ‌{‌ ‌   ‌a:‌ 1,   b: 2 }
isPropertyPresent(obj, ‘c’) ‌‌-> false 
isPropertyPresent(obj, ‘b’) ‌‌-> true
```
2.Write a function called getAllKeys that takes an object as a parameter and returns an array of keys of all the properties in the object.
```js
‌‌‌‌function‌‌ ‌‌getAllKeys(‌object‌)‌ ‌{‌ ‌
   ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌
}‌ ‌ 
 var‌‌ ‌‌obj‌ ‌‌=‌‌ ‌{‌ ‌   ‌a:‌ 1,   b: 2 }
 getAllKeys(obj) -> ‌‌[‘a’, ‘b’]
 ```
HINT: Use object.keys()

3.Write a function called getAllValues that takes an object as a parameter and returns an array of all the values from that object.
```js
‌‌‌‌function‌‌ ‌‌getAllValues(‌object‌)‌ ‌{‌ ‌  
 ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌
}‌
var‌‌ ‌‌obj‌ ‌‌=‌‌ ‌{‌ ‌   ‌a:‌ 1,   b: 2 } 
getAllValues(obj) ‌‌-> ‌‌[1, 2]
```
HINT: Use object.values()
4.Write a function called transformFirstAndLast that takes an array as a parameter and returns an object with one property where: The first element of the array is the key. The last element of the array is the value.
```js
‌‌‌‌function‌‌ ‌‌transformFirstAndLast(‌array)‌ ‌{‌ ‌   ‌‌
//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌ 
}‌
 ‌var array = ['Queen', 'Elizabeth', 'Of Hearts', 'Beyonce']  
transformFirstAndLast(array) -> ‌‌{ Queen: ‘Beyonce’ }
```
5.Write a function called extend that takes two objects and adds all the properties of the second object to the first object if the property’s key does not already exist.
```js
function‌‌ ‌‌extend(‌object1, object2)‌ ‌{‌ ‌ 
  ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌ 
}‌ ‌ 
 var‌‌ ‌‌obj1 = ‌‌{    ‌a:‌ 1,    b: 2 }
 var‌‌ ‌‌obj2 = ‌‌{    b:‌ 4,    c: 3 } 
 console.log‌(obj1) ‌‌-> ‌‌{a: 1, b: 2} 
 extend(obj1, obj2)
 console.log‌(obj1) ‌‌-> ‌‌{a: 1, b: 2, c: 3}
 ```
6.Write a function called countAllCharacters that takes a string as a parameter and returns an object with each unique character as a key and the value is the amount of times it appears in the string. If the string is empty it should return an empty object.
```js
‌‌‌‌function‌‌ ‌‌countAllCharacters(‌string)‌ ‌{‌
   ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌
 }‌ ‌ 
countAllCharacters(‘hello’)‌‌ -> ‌‌{ h: 1, e: 1, l: 2, o: 1 } ‌‌
countAllCharacters(‘banana’)‌‌ -> ‌‌{ b: 1, a: 3, n: 2 }
```
7.Write a function called countWords that takes a string as a parameter and returns an object with each unique word as a key and the value is the amount of times it appears in the string If the string is empty it should return an empty object.
```js
‌‌‌‌function‌‌ ‌‌countWords(‌string)‌ ‌{‌ ‌  
 ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌
 }‌ ‌
countWords ('ask a bunch get a bunch’) -> { ask: 1, a: 2, bunch: 2, get: 1 }  ‌‌
countWords (‘’) ‌-> ‌‌{}
```
8.Write a function called convertObjectToList that takes an object as a parameter and returns an array where each element is an array with the key as the first element and the value as the second.
```js
‌‌‌‌function‌‌ ‌‌convertObjectToList(‌object)‌ ‌{‌
 ‌   ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌
 }‌ ‌  
var‌‌ ‌‌obj = ‌‌{    ‌name:‌ ‘holly’,    age: 35,    role: ’producer’ } 
 ‌convertObjectToList(obj) -> ‌ [[‘name’, ’holly’], [‘age’, 35], [‘role’, ’producer’]]
 ```
9.Write a function called select that takes two parameters, an object and an array. It then returns a new object with properties from the passed object whose keys were found in the array as elements.
```js
‌‌‌‌function‌‌ ‌‌select(‌array, object)‌ ‌{‌
 ‌   ‌‌//Write‌ ‌your‌ ‌code‌ ‌here‌ ‌
 }‌ ‌  
var‌‌ ‌‌arr = [‘a’, ’b’, ’e’]
var‌‌ ‌‌obj = ‌‌{    a: 1,    b:‌ 2,    c: 3,    d: 4 } 
select(arr, obj) ‌-> ‌‌{ a: 1, b: 2 }
```
