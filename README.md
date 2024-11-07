[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/j2rELqlE)

# Assignment 2

Work in `src/` directory. Ignore other files, just use or create a new js file and solve the following questions in it. Sometimes it might be better to create additional files for different tasks. For example, if you are working on a task that requires a lot of code, you can create a separate file for that task.
Variables; Data Types (number, string, boolean, undefined, null); prompt; comparison and logical operators; type conversion

1. Declare a variable and assign a string as a value. Make sure the string is at least 6 characters long. Print the variable to the console.
2. What is the difference between "5" and 5?
   "5" - aris stringi da 5-aris ricxvi
3. Declare a variable and assign a number as a value. Make sure the number is greater than 9. Print the variable to the console.
   let number = 12;
   console.log(number);
4. Declare a variable and assign a boolean as a value. Print the variable to the console.
   let age = true;
   console.log(age)
5. What operators give us a boolean result?
   true or false
6. Declare a variable with the value of "Hello". Covert the value to upper case and print the converted value to the console.
   let word = hello;
   console.log(word.toUpperCase());
7. Declare another variable with the value of "World". Convert the value to lower case and print the converted value to the console.
   let word = world;
   console.log(word.toLowerCase);
8. Given code:
   ```javascript
   let text = "Hello";
   text.toUpperCase();
   console.log(text);
   ```
   What is the value of the variable `text` before and after the method is called?
   HELLO
9. Given code:
   ```javascript
   let text;
   console.log(text);
   ```
   What is the value of the variable `text`?
   " undefined iqneba "
10. Find an error in the following code:
    ```javascript
    let text = "Hello";
    console.log(text.toLowercase());
    ("swori iqneba toLowerCase");
    ```
11. Find and fix the error in the following code:
    ```javascript
    let age = prompt("How old are you?");
    let nextAge = age + 1;
    console.log(`Next year you will be ${nextAge}`);
    (" promt abrunebs strings da amitom swori iqneba: let nextAge = Number(age) + 1;");
    ```
12. Finish the code:
    ```javascript
    let name = prompt('What is your name?');
    let age = Number(prompt('How old are you?'));
    let isInSixties "= age == 60"  // finish the code so that it prints true if the age is in 60s
    console.log(`${name} is in sixties: ${isInSixties}`);
    ```
13. What is the value of `x`?
    ```javascript
    let x = 5;
    console.log(x++);
    console.log(x);
    ("x = 6");
    ```
14. What is the value of `y`?
    ````javascript
    let y = 5;
    console.log(++y);
    console.log(y);
    ```y = 6
    ````
15. What is `x++` and `x--`?
    x++ aris mnishvnelobis gazrda Shemdeg, xolo x-- amcirebs migebul ricxvs
16. What is the difference between `++x` and `x++`?
    ++x aris before xolo x++ after
17. If we try to declare variable without any value, what will be the value of the variable in the console?
    am shemtxvevashi undefined iqneba
18. Show the example of equality operator.
    let x = "3";
    let z = 3;
    console.log(x == z);
19. Show the example of not equal operator.
    let x = "3";
    let z = 3;
    console.log(x !=z);
20. What's going on when we try to add string and number?
    ubralod miewereba ar shekrebs da arc gamoaklebs
