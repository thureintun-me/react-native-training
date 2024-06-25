## JavaScript Coding Assignment: Understanding and Logic

### Part 1: Variables (`let`, `const`, `var`)

#### 1. Understanding Variable Scoping

- **Task 1:** Declare a variable using `var` inside a function and log its value both inside and outside the function. Explain the output in comments.

    ```javascript
    // Example for `var`
    function testVar() {
        var x = 10;
        console.log("Inside function:", x); // Output: Inside function: 10
    }
    testVar();
    console.log("Outside function:", x); // Output: Explain the output
    ```

- **Task 2:** Declare a variable using `let` inside a block and log its value both inside and outside the block. Explain the output in comments.

    ```javascript
    // Example for `let`
    {
        let y = 20;
        console.log("Inside block:", y); // Output: Inside block: 20
    }
    console.log("Outside block:", y); // Output: Explain the output
    ```

- **Task 3:** Declare a constant using `const` and try to reassign it. Explain what happens in comments.

    ```javascript
    // Example for `const`
    const z = 30;
    console.log("Initial value:", z); // Output: Initial value: 30
    z = 40; // Output: Explain the output
    ```

### Part 2: Functions

#### 1. Function Declaration

- **Task:** Write a function declaration named `greet` that takes a name as a parameter and logs "Hello, `name`!".


#### 2. Function Expression

- **Task:** Convert the above function into a function expression and assign it to a variable named `greetExpression`.


#### 3. Immediately Invoke Function

- **Task:** Write an function that takes two numbers and returns their sum. Immediately invoke this function with the numbers 5 and 10.


### Part 3: Objects

#### 1. Object Creation and Property Access

- **Task:** Create an object named `student` with properties `name`, `age`, and `course`. Log each property to the console.

#### 2. Object Methods

- **Task:** Add a method to the `student` object named `introduce` that logs "Hi, I am `name` and I am `age` years old." Invoke this method.


#### 3. Logic Application: Object Manipulation

- **Task:** Write a function `updateStudent` that takes a student object and a key-value pair, updates the student object with the new key-value pair, and returns the updated object.


### Part 4: Truthy and Falsy Values

#### 1. Filtering Falsy Values

- **Task:** Create an array with a mix of truthy and falsy values. Write a function that filters out the falsy values and returns a new array with only truthy values.

#### 2. Checking Truthy and Falsy

- **Task:** Write a function that takes a value and logs whether it is truthy or falsy.


### Common Logic Functions

#### 1. Checking Even or Odd

- **Task:** Write a function `isEven` that takes a number as an argument and returns true if the number is even, otherwise false.


#### 2. Reversing a String

- **Task:** Write a function `reverseString` that takes a string as an argument and returns the reversed string.


#### 4. Checking Palindrome

- **Task:** Write a function `isPalindrome` that takes a string as an argument and returns true if the string is a palindrome (reads the same forward and backward), otherwise false.


#### 5. Checking Leap Year

- **Task:** Write a function `isLeapYear` that takes a year as an argument and returns true if the year is a leap year, otherwise false.


#### 6. Finding Maximum Number

- **Task:** Write a function `findMax` that takes an array of numbers as an argument and returns the maximum number in the array.

 
#### 7. Counting Vowels

- **Task:** Write a function `countVowels` that takes a string as an argument and returns the number of vowels (a, e, i, o, u) in the string.


#### 8. Capitalizing Words

- **Task:** Write a function `capitalizeWords` that takes a string as an argument and returns the string with the first letter of each word capitalized.

    





