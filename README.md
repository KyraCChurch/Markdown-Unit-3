# React Beta Docs Quick Start Explanation   
## Week 18 Day 1

In this example we have two buttons. Each button when clicked has its own click count. The fact that each button has it's own count relates to each button having its own state which holds its own count. It starts by setting the useState to 0 and then updating the individual setCount to be count + 1 wehenever clicked.

# Week 19 Day 2

1. A web aplication that rewrites the current web page with new data instead of loading a new web page.

2. REACT is an open-source front-end JavaScript library for building user interfaces based on UI.

3. JSX is a React extension and it is a syntax extension to JavaScript.

4. Babel is a JavaScript transpiler that converts edge JavaScript(ES6) into plain old ES5 JavaScript that can run in any browser including old ones.

5. Webpack is an open-source module bundler for JavaScript. Its main purpose is to bundle JavaScript files for usage in a browser.

6. Create React App is an environment for learning React, and is a way to start building a new single-page application in React.

# Week 19 Day 3

1. The five most basic types of data are strings, numbers, booleans, undefined, and null.

2. - The var keyword has traditional variable declaration syntax. It is optional to initialize a variable with a value if it is declared with the var keyword. If developers do not initialize it with a value, JavaScript will automatically assign undefined to it.

![let example](https://i.im.ge/2022/12/03/SERYV9.574B0A4E-FD35-4924-A301-AA7DE042EECB-1-201-a.jpg).

- The let keyword should be used in situations where you want to declare a variable that should be restricted to the block in which it is restricted. Also, variables declared with the let keyword cannot be updated or re-declared.

![let example](https://i.im.ge/2022/12/03/SERyDS.6B526B13-D56F-4DE1-8BFC-1B7F2F81B965-1-201-a.jpg).

- The const keyword follows the same rules as the let keyword. The only difference with const is that const is used to define only constant values in JavaScript programs.

![const example](https://i.im.ge/2022/12/03/SE8vGS.35901894-0853-4C87-A85F-8797EC3E84BE-4-5005-c.jpg).

3. 
- Pass-by-reference: When a method is called, the method arguments reference the same variable in memory as the caller.  
An object is a reference type because it is not storing the data but is a reference to the location where the data is stored.
- Pass-by-value: When a method is called, the caller passes a copy of the argument variables to the method resulting in two values in memory. 
String is pass by value because the string variable holds the reference to the actual data, so it passes this reference and not the actual data.

4. Map, filter, and reduce help make code shorter and simpler.  
The map() method is used for creating a new array from an existing one.  
The filter() method takes each element in an array and it applies a conditional statement against it.  
The reduce() method reduces an array of values down to just one value. 

5.  The Falsy Values in Javascript are undefined , null , NaN , 0 , "" (empty string), and false. These are important for comparisons and conditionals within a boolean value.

6. The async and await keywords enable asynchronous, promise-based behavior to be written in a cleaner style

7. The async function declaration declares an async function where the await keyword is permitted within the function body.

8. The try statement allows you to define a block of code to be tested for errors while it is being executed.  
The catch statement allows you to define a block of code to be executed, if an error occurs in the try block.