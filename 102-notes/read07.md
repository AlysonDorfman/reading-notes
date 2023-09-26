[Back to Homepage](https://alysondorfman.github.io/reading-notes/)

# Read: 07 - Programming with JavaScript

## Control Flow

Control Flow is the order in which the computer executes statements in a script. 
    - Default is 1st line to last line of code
    - The order changes when there's a **condition** or **loop**

## JavaScript Functions

A function is a block of code designed to perform a particular task. 

**How to invoke or "call" a function:** 
    - Event: such as a user click
    - When written in JavaScript code to invoke
    - Automattically, self-invoked

## Syntax of a function

function functionName(parameter1, parameter2, parameter3) {
    //code to be executed
}

**Parameters:** "arguments" behave like local variables, so their value is whatever the value is __at the exact time__ the function is invoked

## Function Return

//let x = myFunction(4,3);

//function myFunction(a,b) {
    return a*b
}

## Local Variables

You can declare a variable within a function, but then is can only be used in that function. Therefore, you can use a variable with the same name throughout your code as long as is stays within a function.