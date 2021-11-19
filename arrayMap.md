# ✍️ Notes

1. What is the definition of Array.map?

- The map() method creates a new array populated with the results of calling a provided function AKA a callback function on every element in the calling array. 

2. What data type can you call map on?

- array

3. What does the pseudocode for map look like?

- array.map(callback(currentValue, index, arr)thisValue);

4. What are the 2 input arguments for map?

- callback function
- contextual thisArg(optional)

5. What are the arguments the callback function takes in?

- element
- index (optional)
- array (optional)
    
6. What is currentValue referring to?

- The value of the current element in the array that map is looking at. 

7. What is the output of map?

- A new array with each element being the result of the callback function. 

8. Does map mutate the original array?

- Map does NOT muatate the original array. 

9. What does it mean when an argument is optional?

- An optional argument means that map does not care if you pass it a value or not. 

10. What is the only difference between Array.forEach and Array.map?

- The only difference between forEach and map is that .map() will always return a new array of the same length as the original array comprised of your return values and forEach will always return undefined.
    