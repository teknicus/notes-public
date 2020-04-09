# Fireship.io JavaScript Course



### 1) The Weird History of JS

##### Keywords:

- DOM - Document Object Model
- ECMA - European Computer Manufacturers Association
- NodeJS Event Loop - Event Driven Non Blocking
- **SvelteJS**
-  Bundlers- Webpack, Rollup
-  Utils - ImmutableJS, RXJS
- JIT Compiler - Just In Time Compiler (Interpreter)



### 2) JS: How Its Made

##### Notes

-  JS is an Interpreted Language
-  Dynamically typed - No typedefs - Datatypes known at runtime
- MultiParadigm
- Prototypal Inheritance
-  JS V8 Implementatipn - https://youtu.be/FSs_JYwnAdI?t=290
-  Single Threaded
- Memory
  - Call Stack
    - High Performance
    - Continuous region 
  - Heap
    - Unstructured 
    - Objects within closures are Stored 
- **Event Loop** - https://youtu.be/FSs_JYwnAdI?t=491





##### Tools

- Chrome dev tools -> Sources tab can be used to examine execution frame-by-frame
- **StackBlitz**  - to run JS code examples in an isolated sandbox in the browser
- Quokka Plugin for JS Code - View output in code editor



### 3) JS Survival Guide

##### Notes

-  Use the `defer` tag withing HTML *`script`* tag to load JS only after loading the remainder of the page

  - ```html
    <script defer src="./index.js"></script>
    ```

-  Primitives 

  - Basic Primitives in JS
  
    -  Boolean
    -  Null
    -  Undefined
    -  Number
    -  BigInt
    -  String
    -  Symbol
  
  -  Value can't be directly changed once they have been assiegned to a variable.
  
  -  ```javascript
     typeof  23; // number
     typeof "foo" // string
     typeof null // null
     
     typeof {} // object
     typeof [] // object
     typeof function() {} // function (which inherits from object)
     ```
  
  -  Anything that is not a primitive is an [Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object), or a descendant of it. Objects are collections of key/value pairs and  used as the building block for more complex data structures.
  
-  Truthy vs Falsy

   -  If you’re unsure about a value, you can convert it using the logical `!` NOT operator twice

   -  Examples:

      ```javascript
      true; // true
      !! "hello"; // true
      !! -1; // true
      !! []; // true
      !! {}; // true
      
      false; // false
      !! null; // false
      !! undefined; // false
      !! 0; // false
      !! ""; // false
      ```

-  Control Statements

   -  if...else if...else

   -  switch case

   -  try...catch....finally

      -  ```javascript
           try{
               
           } catch(error){
           	//runs if there's an error
           } finally{
             //runs after try and catch  
           }
         ```

-  Variables

   -  `var` used to declare a general purpose variable. The value can be reassigned.
   -  Hoisting : Even if a variable is declared later on in the program in global scope, the compiler raises all the declarations to the top to avoid scope resolution errors. However, the value is still assigned only when encountered in sequential order
   -  `let` is like `var` but limited to the scope of a code block
   -  use `const` to avoid overwriting variable values

-  Functions