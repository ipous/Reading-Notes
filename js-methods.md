# ✍️ Notes

1. List some of JavaScript's data types:

- objects, strings, arrays, and booleans and numbers are all data types. There are more as well.

2. In JavaScript, almost____ everything is an object.

- almost everything is an object in JS -arrays, booleans, more All JS values, except primitives, are objects

3. What are "JavaScript Primitives"?

- A primitive value is a value that has no properties or methods. A primitive data type is data that has a primitive value.

4. How many primitive data types are there?

- There are 7 data types. string, number, boolean, undefined, symbol, and null.

5. What are the three JavaScript Primative Wrapper types?

- JS provides three primitive wrapper types, : Boolean, Number, and string types.

6. What does a JavaScript Primative Wrapper do?

- make it easier to call JS built in methods on the primitive value.

7. What is the Primative Wrapper doing under the hood when you call a method on a variable that holds a number, a string, or a boolean?

- JS will create an object of a coresponding type. Then call the method on the instance. JS deletes the instance immediatly after it is finished with it 
and moves onto the next script.

8. What are functions that are binded to an object called?

- methods

9. So if almost everything in JavaScript is an object, what does that mean for most data types?

- most data types will have their very own special methods built into JS.

10. What do these special built-in methods do?

- a method can accomplish any number of poplar tasks in programming. A few popular tasks are: adding values, removing values, moving values, modyfying values or reading values.

11. How do we access a method on an object?

- dot notation

12. How do we use a built-in method on a JavaScript data type?

- We use dot notation on the variable name to invoke the method. 

13. What kind of built-in methods are we going to learn about in 301?

- string methods
- array methods
- object methods
- number methods
- math methods

14. Where can you go to learn about the different methods avaiable to each data type?

- google it
- MDN web docs
- w3Schools

15. How am I suppose to know what to search for in Google?

- An easy way to search for methods that would help solve your algorithm is to use this pattern: -"how to" + :do the thing" + "data type" + "JS"