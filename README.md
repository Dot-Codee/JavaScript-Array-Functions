# JavaScript-Array-Functions
Hello and welcome to this tutorial on commonly used JavaScript Array methods! We will be discussing some of the most useful methods for working with arrays in JavaScript.

First, let's start with the `.push()` method. This method allows you to add one or more elements to the end of an array. Here's an example:

Copy code
let numbers = [1, 2, 3];
numbers.push(4, 5, 6);
console.log(numbers); // Output: [1, 2, 3, 4, 5, 6]
Next, we have the `.pop()` method, which removes the last element from an array and returns it. For example:

```
let numbers = [1, 2, 3, 4, 5, 6];
let last = numbers.pop();
console.log(numbers); // Output: [1, 2, 3, 4, 5]
console.log(last); // Output: 6
```

Another useful method is the `.shift()` method, which removes the first element from an array and returns it. Here's an example:

```
let numbers = [1, 2, 3, 4, 5, 6];
let first = numbers.shift();
console.log(numbers); // Output: [2, 3, 4, 5, 6]
console.log(first); // Output: 1
```
On the other hand, if you want to add an element to the beginning of an array, you can use the .unshift() method. Here's an example:

```
let numbers = [1, 2, 3];
numbers.unshift(0);
console.log(numbers); // Output: [0, 1, 2, 3]
```
Another commonly used method is the `.slice()` method, which allows you to extract a portion of an array and return it as a new array. You can specify the start and end indices of the slice, like this:

```
let numbers = [1, 2, 3, 4, 5, 6];
let slice = numbers.slice(2, 5);
console.log(slice); // Output: [3, 4, 5]
```
Finally, let's talk about the `.splice()` method. This method allows you to add or remove elements from an array at a specific index. Here's an example of how to remove elements:

```
let numbers = [1, 2, 3, 4, 5, 6];
numbers.splice(2, 3);
console.log(numbers); // Output: [1, 2, 6]
```
And here's an example of how to add elements using `.splice()`:

```
let numbers = [1, 2, 3, 4, 5, 6];
numbers.splice(2, 0, 3.5, 4.5);
console.log(numbers); // Output: [1, 2, 3.5, 4.5, 3, 4, 5, 6]
```

These are just a few of the many useful array methods available in JavaScript. I hope this tutorial has been helpful in getting you started with working with arrays in your code. **Happy Coding**
