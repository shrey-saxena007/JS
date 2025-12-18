## Types of Functions -:
1. Named : normal
2. Anonymous : A function that does not have a name. It is usually assigned to a variable or used as a callback. Since it has no name, it cannot be called directly.
   ```js
      const greet = function() {
        return "Hi there!";}
      console.log(greet()); // Hi there!
   ```
3. Function Expression : When you assign a function (can be named or anonymous) to a variable. The function can then be used by calling that variable.
4. Arrow Functions : A new way to write functions using the => syntax. They are shorter and do not have their own this binding, which makes them useful in some cases.
   ```js
         const square = n => n * n;
         console.log(square(4)); // 16
   ```
5. Callback Function: A callback function is passed as an argument to another function and is executed after the completion of that function.

   ```js
   function num(n, callback) {
       return callback(n);
   }
   
   const double = (n) => n * 2;
   
   console.log(num(5, double));
   ```
6. Async Function : Functions that handle asynchronous tasks. Declared with async, they return a Promise, and you can use await inside them to pause until another Promise resolves.
   ```js
   async function fetchData() {
     return "Data fetched!";
   }
   fetchData().then(console.log); 
   ```
7. Higher Order
8. Nested Functions 





