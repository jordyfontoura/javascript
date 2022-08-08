## Statements

## Arithmetic Operators

- \+
- \-
- \*
- \*\*
- /
- %
- \+\+
- \-\-

## Assignment Operators

- =
- \+=
- \-=
- \*=
- /=
- %=

## String Operators

- \+
- \+=

## Comparison Operators

- ==
- ===
- !=
- !==
- \>
- <
- \>=
- <=

## Ternary Operator

```js
(x>y) ? x : y
```

## Logical Operators

- &&
- ||
- !

## Typeof Operator

The typeof operator returns the type of a variable, object, function or expression:

```js
typeof "John"                 // Returns string
typeof 3.14                   // Returns number
typeof NaN                    // Returns number
typeof false                  // Returns boolean
typeof [1, 2, 3, 4]           // Returns object
typeof {name:'John', age:34}  // Returns object
typeof new Date()             // Returns object
typeof function () {}         // Returns function
typeof myCar                  // Returns undefined (if myCar is not declared)
typeof null                   // Returns object
```

Please observe:

The data type of NaN is number
The data type of an array is object
The data type of a date is object
The data type of null is object
The data type of an undefined variable is undefined

## Delete Operator
The delete operator deletes a property from an object:
```js
const person = {
  firstName:"John",
  lastName:"Doe",
  age:50,
  eyeColor:"blue"
};
delete person.age;   // or delete person["age"];
```

## In Operator
The in operator returns true if the specified property is in the specified object, otherwise false:

```js
// Arrays
const cars = ["Saab", "Volvo", "BMW"];
"Saab" in cars          // Returns false (specify the index number instead of value)
0 in cars               // Returns true
1 in cars               // Returns true
4 in cars               // Returns false (does not exist)
"length" in cars        // Returns true  (length is an Array property)

// Objects
const person = {firstName:"John", lastName:"Doe", age:50};
"firstName" in person   // Returns true
"age" in person         // Returns true

// Predefined objects
"PI" in Math            // Returns true
"NaN" in Number         // Returns true
"length" in String      // Returns true
```

## Instanceof Operator
The instanceof operator returns true if the specified object is an instance of the specified object:

```js
const cars = ["Saab", "Volvo", "BMW"];

(cars instanceof Array)   // Returns true
(cars instanceof Object)  // Returns true
(cars instanceof String)  // Returns false
(cars instanceof Number)  // Returns false
```
