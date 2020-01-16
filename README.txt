# Javascript2019
Learning Javascript in 2019

- Events are "things" that happen to HTML elements
- An HTML event can be something the browser does, or something a user does

1. Event = onClick() - the user clicks an HTML element (ex. button)
2. Code => Change the text inside the <p> tag
    document.getElementById('demo').innerHTML = 'Help Came!'

    document => Refers to the web page
    getElementById() => Access a specific HTML item by ID
    innerHTML => Access the text between two like tags

- Javascript code must be inserted in <script> tags
-A JavaScript function is a block of JavaScript code, that can be executed when "called" for;
  - A function can be called when an event occurs, like when the user clicks a button

- An alert box (popup box) is often used if you want to make sure information comes through to the user
   - You would need to create a function, then add alert("add text");

- var: variable (variables are containers for storing data values)
- parseInt: turns strings into integers/numbers
- onmouseover: The user moves the mouse over an HTML element
- onmouseout: The user moves the mouse away from an HTML element

- Swapping: back and forth between things (ex. images)
- src: source
- Strings: letters/words

CSS in JavaScript
- use .style.

Random Logic
- Math.random: returns a random number between 0 (inclusive),  and 1 (exclusive)
- if/else statement: part of "conditional" statements, which are used to perform different actions based on different conditions
    - executes a block of code if a specified condition is true. If the condition is false, another block of code can be executed
        - Use if to specify a block of code to be executed, if a specified condition is true
        - Use else to specify a block of code to be executed, if the same condition is false
        - Use else if to specify a new condition to test, if the first condition is false
        - Use switch to select one of many blocks of code to be executed

Form Validation:
- Forms take in information
- To validate a form means to check the information and make sure it is correct
.length: how many characters are in something
- || is "or"

=== - equal value and equal type/ used for strings/text - go through every part of the data so its exactly the same
&& - and
== - used for numbers - only goes so deep that it doesn't check that much
