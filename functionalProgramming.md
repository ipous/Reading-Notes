# Notes 
## 1. What is functional programming?

### Functional programming is a style of building the structure of computer programs that treats calculations as evaluations of mathematic functions and avoids changing-state data.

## 2. What is a pure function and how do we know if something is a pure function?

### A pure function returns the same result when given the same arguments. We can tell if something is a pure function if the result is the same when the same argument is given, and if it does not cause any side effects. 

## 3. What are the benefits of a pure function?

### Pure functions are easier to test, create, and understand.

## 4. What is immutability?

### Immutability is a data object with a state that can't be changed. If you want a altered immutable object, you need to create a new one. 

## 5. What is Referential transparency?

### Referential transparency is a pure function that uses immutable data.

## 6. What is a module?

### A module is a file containing related code.

## 7. What does the word ‘require’ do?

### Require lets you use modules in other files.

## 8. How do we bring another module into the file the we are working in?

### We use require('./fileExample'); We don't need to add the file type. (app.js is just './app')

## 9. What do we have to do to make a module available?

### We have to export the module from the file it exists in; module.exports = fileExample; This makes it available in every file.

---

## Resources
- [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

- [Node JS Tutorial for Beginners- Modules and Require](https://www.youtube.com/watch?v=xHLd36QoS4k)