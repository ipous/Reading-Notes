# ✍️ Notes

1. What are loops used for in programming?

- For running the same code over and over again, with a different value every time.

2. What are the 5 different types of loops we work with in JavaScript?

- for loop
- while loop
- do...while
- for...in
- for...of

3. What is the definition of a for loop?

- It creates a loop that consists of three optional expressions, enclosed in parentheses
and seperated by semicolons, followed by a statement (usuallty a block statement to be executed in the loop.

4. What is the syntax and pseudocode of a for loop?

- for(initialExpression; conditionalExpression; iteratorExpression) {
 code block to run at every iteration;
 };

5. What does the initial expression do?

- Ran once at the very beginning of the for loop and it initializes the variable used in the loop.

6. Why is it important to use `let` when declaring the `i` variable in a loop?

- When let is used to declare the i variable in a loop, the i variable will only have scope within the loop.

7. What does the conditional expression do?

- Defines the condition for the loop to run. If condition returns true, the loop will start over again, if it returns false, the loop will end.

8. What does the iterator expression do?

- increments/decrements the value of the initial variable and moves the loop to the next iteration.

9. When a for loop executes, the following occurs:

- STEP 1: The initializing expression is executed once and initializes a loop counter.
- STEP 2: The conditional exression is evaluated. If it evaluates true, the loop statements execute. If it evaluates to false, the loop ends.
- STEP 3: The statements inside the code block execute.
- STEP 4: Then the iterator expression is executed and either increments or decrements the loop to the next iteration.
- STEP 5: Lastly, we circle back up to STEP 2 and the for loop continues to run until the condition returns false.

10. What is a callback function?

- A function that is passed as an argument to another function.

11. When do we use a callback function?

- It can only run after another function has finished and it will most commonly used with Javascript built-in methods.