# Chapter 2- Program Structure

Expressions and Statements
---
1. A fragment of code that produces a value is called an **expression**.  
2. Every value that is written literally is called an **Expression**. For example:  
```
22
"Saturday"
```
3. An expression between parentheses is also an **expression**.  

The simplest kind of **statements** is an expression with a semicolon after it.
```
1;
true;
```
  
Bindings
---
To catch and hold values, JavaScript provides a thing called a _binding_ or _variable_
```ecmascript 6
let caught = 5 * 5;
console.log(caught);
// -> 10
```

The = operator can be used anytime to change values from the bindings. Imagine **Bindings** or 
**Variables** is a tentacle not Boxes. They _do not contained values_ but they _grasp them_. 
Example:  
```ecmascript 6
let sayudhaDebt = 20;
sayudhaDebt = sayudhaDebt - 5;
console.log(sayudhaDebt);
// -> 15;
``` 

if a _variable_ or _binding_ has no value, you'll get the value _undefined_  



