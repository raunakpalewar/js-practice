
## js-practice

This is JavaScript code for learning and concept building.

## JavaScript Display

- **Using innerHTML:** To dynamically update the content in any HTML tag using an ID.
- **Using document.write():** Also helps to dynamically write text in any HTML tag (this method is not recommended; it should only be used while testing).
- **Using alert():** To bring an alert box in the document; it is used for warning or confirmation.
- **console.log():** Mainly used for debugging to display data in the browser.

## Additional Important Notes

- JavaScript is executed one by one in the same order as they are written.
- Each JavaScript statement is separated by a semicolon (it is not compulsory but is recommended for writing clean code).
- JavaScript statements can be grouped together inside curly brackets `{}` like in functions.
- JavaScript keywords: `var`, `let`, `const`, `if`, `switch`, `for`, `function`, `return`, `try`.
- JavaScript is case-sensitive.
- Hyphen (`-`) cannot be used for naming variables; it is reserved for subtraction.
- The `$` sign is also used in naming variables; it is usually used in jQuery to select all.

## How to Define Variables in JavaScript

- **Var:** It is an older method; try to use it less, always have global scope, does not have block scope.
- **Let:** Introduced in 2015, it has global scope or function scope.
- **Const:** Introduced in 2015 and is used to declare variables whose values cannot be changed, cannot be redeclared, reassigned, and have block scope. Use `const` when declaring arrays, objects, functions, and regex.

## JavaScript Operators

1. **Assignment Operator:** `=`
2. **Arithmetic Operator:**
   - Addition: `+`
   - Subtraction: `-`
   - Multiplication: `*`
   - Exponential: `**` (produces the same result as `Math.pow(x,y)`)
   - Division: `/`
   - Modulus: `%`
   - Increment: `++`
   - Decrement: `--`
3. **Comparison Operator:**
   - Equal to: `==`
   - Compare values and type: `===`
   - Not equal: `!=`
   - Not equal value and not equal type: `!==`
   - Greater than: `>`
   - Smaller than: `<`
   - Ternary: `?`
   - Greater than or equal to: `>=`
   - Smaller than or equal to: `<=`
4. **Logical Operator:**
   - AND: `&&`
   - OR: `||`
   - NOT: `!`
5. **Type Operator:**
   - `typeof`: Returns the type of the variable.
   - `instanceof`: Returns true if the object is an instance of the specified object type.

### String Concatenations

- The `+` operator is used to concatenate two strings; it is also called the concatenation operator.
- If you put a number in quotes, then the rest of the numbers will be treated as a string and get concatenated, not added (this property does not apply to the numbers written before and without quotes).
- When adding a number and a string, JavaScript will treat the number as a string.

## Data Types in JavaScript

1. **String**
2. **Number:** Decimal and non-decimal number; mainly, all numbers are stored as decimal numbers (e.g., `34` is stored as `34.00`).
3. **BigInt:** All JavaScript numbers are stored in a 64-bit floating-point format; `BigInt` is used to store integer values that are too big.
4. **Boolean:** `true`, `false`
5. **Undefined**
6. **Null**
7. **Symbol**
8. **Object:**
    - **Object:**
        - JSON-like structure.
        - It is written inside `{}` in a key-value pair.
        - To access object value, it is written in two ways: `objectName.key` or `objectName['key']`.
    - **Array:** Written with square brackets (e.g., `cars =['tata','volvo','mahindra']`).
    - **Date**

## JavaScript Functions

> Block of code written to perform a particular task.

> Syntax:
>
> ```javascript
> function functionName() {  
>     //code  
> }
> ```

> Functions can have parameters also.

## Javascript Events 

- Event is created to trigger the working of any js function using html

- Types of Event :
    1. 'onchange'
    2. "onclick"
    3. "onmouseover"
    4. "onmouseout"
    5. "onmouseout"
    6. "onkeydown"
    7. "onload" ...etc

**Js Event Handler**

- Event handlers can be used to handle and verify user input, user actions, and browser actions:

1. Things that should be done every time a page loads
2. Things that should be done when the page is closed
3. Action that should be performed when a user clicks a button
4. Content that should be verified when a user inputs data

- Many different methods can be used to let JavaScript work with events:

1. HTML event attributes can execute JavaScript code directly
2. HTML event attributes can call JavaScript functions
3. You can assign your own event handler functions to HTML elements
4. You can prevent events from being sent or being handled

## Javascript string

1. used to store text
2. can be written using ' or "

- String Methods
1. .lenght
2. .charAt()
3. .charCodeAt()
4. .at()
5. .slice()
6. .substring()
7. .substr()
8. .toUpperCase() or .toLowerCase()
9. .concat()
10. .trim()
11. .repeat()
12. .replace()
13. .split()

- to substitue a value in place of a variable then we can use ${} to substite the value it is also called string interpolation


## JavaScript Arrays

- Used to store multiple values in a single variable.
- Can be written using square brackets `[]`.
- Example: `let fruits = ['apple', 'banana', 'orange'];`

### Array Methods

1. `length`
2. `push()`
3. `pop()`
4. `shift()`
5. `unshift()`
6. `indexOf()`
7. `splice()`
8. `slice()`
9. `concat()`
10. `reverse()`
11. `sort()`

## JavaScript Objects

- Used to store keyed collections of various data and more complex entities.
- Written inside curly brackets `{}` in a key-value pair.
- Example: 
    ```javascript
    let person = {
        name: 'John',
        age: 30,
        city: 'New York'
    };
    ```

### Object Methods

- `Object.keys()`
- `Object.values()`
- `Object.entries()`

## JavaScript Math

- Provides many methods for performing mathematical tasks.
- Example: `Math.PI`, `Math.round()`, `Math.floor()`, `Math.ceil()`, `Math.random()`, etc.

## JavaScript Random

- Used to generate random numbers.
- Example: `Math.random()`.

## JavaScript If-Else

- Used for decision-making in JavaScript.
- Syntax:
    ```javascript
    if (condition) {
        // code to be executed if condition is true
    } else {
        // code to be executed if condition is false
    }
    ```

## JavaScript Loops

- Used to repeatedly run a block of code.
- Types: `for`, `while`, `do-while`.

## JavaScript Switch

- Used to perform different actions based on different conditions.
- Syntax:
    ```javascript
    switch (expression) {
        case value1:
            // code to be executed if expression matches value1
            break;
        case value2:
            // code to be executed if expression matches value2
            break;
        default:
            // code to be executed if expression doesn't match any cases
    }
    ```

## JavaScript Sets

- Used to store unique values of any type.
- Example: 
    ```javascript
    let mySet = new Set();
    mySet.add(1);
    mySet.add(2);
    ```

## JavaScript Maps

- Used to store key-value pairs.
- Example:
    ```javascript
    let myMap = new Map();
    myMap.set('key1', 'value1');
    myMap.set('key2', 'value2');
    ```

## JavaScript Classes

- Introduced in ECMAScript 2015 (ES6).
- Syntax:
    ```javascript
    class ClassName {
        constructor() {
            // constructor method
        }
        method1() {
            // method1 definition
        }
        method2() {
            // method2 definition
        }
    }
    ```

## JavaScript Arrow Function

- Introduced in ECMAScript 2015 (ES6).
- Provides a more concise syntax for writing function expressions.
- Example: 
    ```javascript
    const add = (a, b) => a + b;
    ```

## jQuery

- A fast, small, and feature-rich JavaScript library.
- Simplifies things like HTML document traversal and manipulation, event handling, and animation.
- Example:
    ```javascript
    $('button').click(function(){
        $('p').hide();
    });
    ```

## AJAX

- Asynchronous JavaScript and XML.
- Used to send and receive data asynchronously without reloading the web page.
- Example:
    ```javascript
    $.ajax({
        url: 'example.php',
        success: function(result){
            $('#div1').html(result);
        }
    });
    ```

## JavaScript Async

- Allows JavaScript to execute asynchronous code.
- Uses `async` and `await` keywords.
- Example:
    ```javascript
    async function myFunction() {
        let promise = new Promise((resolve, reject) => {
            setTimeout(() => resolve("done!"), 1000)
        });

        let result = await promise; // wait until the promise resolves (*)
        alert(result); // "done!"
    }
    ```

## DOM Manipulation

- Document Object Model (DOM) manipulation refers to changing the structure or style of an HTML document.
- Example:
    ```javascript
    document.getElementById('demo').innerHTML = 'Hello, World!';
    ```

## JavaScript Error Handling

- Used to handle errors that may occur in JavaScript code.
- Types of errors: SyntaxError, ReferenceError, TypeError, etc.
- Syntax:
    ```javascript
    try {
        // code that may throw an error
    } catch (error) {
        // code to handle the error
    }
    ```

## JavaScript Promises

- Used for asynchronous programming in JavaScript.
- Represents a value that may be available now, in the future, or never.
- Syntax:
    ```javascript
    const myPromise = new Promise((resolve, reject) => {
        // code to produce a result or an error
    });

    myPromise.then(result => {
        // code to handle the successful result
    }).catch(error => {
        // code to handle the error
    });
    ```

## JavaScript Generators

- A special type of function in JavaScript that can be paused and resumed.
- Used for asynchronous programming and iterating over large datasets.
- Syntax:
    ```javascript
    function* myGenerator() {
        yield 'value1';
        yield 'value2';
        // more yields...
    }
    ```

## JavaScript Fetch API

- Used to make network requests in JavaScript.
- Provides a modern alternative to XMLHttpRequest.
- Example:
    ```javascript
    fetch('https://api.example.com/data')
        .then(response => response.json())
        .then(data => console.log(data))
        .catch(error => console.error('Error:', error));
    ```

## JavaScript Modules

- Used to organize code into reusable components.
- Encapsulate related code into a single file.
- Supported natively in modern browsers and Node.js.
- Syntax (ES6):
    ```javascript
    // Exporting module
    export function myFunction() {
        // code
    }

    // Importing module
    import { myFunction } from './myModule.js';
    ```

## JavaScript Transpilers

- Used to convert code from one programming language to another.
- Example: Babel transpiles modern JavaScript code (ES6+) into older versions (ES5) for compatibility with older browsers.

## JavaScript Bundlers

- Used to bundle JavaScript files together for optimization and performance.
- Example: Webpack bundles multiple JavaScript files into a single file for deployment.

## JavaScript Templating Engines

- Used to generate HTML markup dynamically from JavaScript data.
- Example: Handlebars.js, Mustache.js, etc.

