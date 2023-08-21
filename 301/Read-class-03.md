# Read: Class 03

## Passing Functions as Props

### React Docs - list and keys

1. What does .map() return? Returns a new array from calling a function for every array element.
2. If I want to loop through an array and display each value in JSX, how do I do that in React? Use curly braces and map function.
3. Each list item needs a unique ____. Key
4. What is the purpose of a key? Keys help React identify which items have changed, are added, or are removed.

### The Spread Operator

1. What is the spread operator? Spread syntax allows an iterable, such as an array or string, to be expanded in places where zero or more arguments (for function calls) or elements (for array literals) are expected. 
2. List 4 things that the spread operator can do. It can be used to concatenate arrays, create shallow copies of arrays, convert strings into arrays of characters, merge or clone objects, and dynamically pass values into functions or constructors, among other use cases.
3. Give an example of using the spread operator to combine two arrays. const join = [...team, ...captain];
4. Give an example of using the spread operator to add a new item to an array. const arr_members = ['arun', 'shouvik']; const arr_family = ['banik', ...arr_members];
5. Give an example of using the spread operator to combine two objects into one.const merge = (...objects) => ({ ...objects });

### Videos

1. In the video, what is the first step that the developer does to pass functions between components? Create function
2. In your own words, what does the increment function do? It takes variable and increments(changes) its value.
3. How can you pass a method from a parent component into a child component? Props 
4. How does the child component invoke a method that was passed to it from a parent component? Pass the function reference to the child component as a prop. Then you can call that parent's function from the child component like props.parentMethodName().
