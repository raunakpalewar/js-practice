
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

