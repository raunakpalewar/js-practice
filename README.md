# js-practice

This are the Java script code for learning and concept building


## Javascript Display 
1. using innerHTML : to dynamically update the content in any html tag using id
2. using document.write() : also helps to dynamically write text in amy html tag ( this method is not recommended it should only be used while testing)
3. using alert() : to bring a alert box in the document it is used for worning or confimation 
4. console.log() : it is mainly used for debugging to disply data in the browser

## Additional Important Notes 
1. Javascript is executed one by one in the same order as they are written.
2. Each javascript statement is seperated by ; (it is not compulsarry but is recommeded to writing clean code)
3. javascript statemnetns can be grouped together inside curly brackets {} like in functions
4. Javascript keywords : var , let , const , if , switch , for , function , return , try 
5. Javascript is case sensitive 
6. Hypthen (-) can not be used for naming variables it is reserved for the substraction
7. $ sign is also used in naming variables it is ususlly used in jquery to select all 

## How to define variables in js
1. Var : it is older method try to use it less , always have gloabal scope , does not have block scope 
2. Let : introduced in 2015 , it has global scope or function scope 
3. const : introduce in 2015 and is used to declare variable whose values cannot be changed , cannot be redeclared , reassigned and have block scope .
    use const when declaring array , object , function and regex

## Javascript Operators 

1. Assignment operator =
2. Arithmatic operator :
    a. addition : +
    b. substraction : -
    c. multiplication : *
    d. Expoenetial : ** it produces the same result as Math.pow(x,y)
    e. division : /
    f. mudulas : %
    g. increment : ++
    h. Decrement : --

3. comparision operator :
    a. equal to ==
    b. compare values and type ===
    c. not equal !=
    d. not equal value and not equal type : !==
    e. greater than >
    f. smaller than <
    g. ternary : ?
    h. greater than equal to >=
    i. smaller than equal to <= 

4. Logical Operator :
    a. and &&
    b. or ||
    c. not !

5. Type operator
    a. typeof : return type of variable
    b. instanceof : returns true if object is instance of and object type



### String concatenations
1. + is used to concatenate two strings it is also called concatenation operator
2. if you put a number in quates then rest of the numbers will be treated as string and get concatenated not add (this property does not apply to the numbers written before and without quotes)
3. When adding a number and a string, JavaScript will treat the number as a string.


## Data Types in Javascript
1. String
2. Number : decimal and non decimal number , mainly all the numbes are stored as decimal number ex : 34 is stored as 34.00
3. Bigint : all js numbers are stored in a 64 bit floating point format , bigint is used to store integers values that are too big
4. Boolean : true, false
5. Undefined
6. Null
7. Symbol
8. Object : 
    a. Object : 
        i. json like structure 
        ii. it is writeen insied {} in a key value pair
        iii. to access object value it is written in two ways objectName.key or objectName['key']
    b. array : written with square brackets 
        ex : cars =['tata','volvo','mahindra']
    c. date

## Javascript Functions

>> Block of code written to perform a perticular task.
>> syntax :
    function functionName(){
        //code
    }
>>function can have parameters also

## Javascript Events 