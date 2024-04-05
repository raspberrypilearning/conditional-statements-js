In JavaScript, conditional statements are used to make decisions in your code based on certain criteria. These conditions are checked to see if they are true or false, and the code is then executed based on these choices. There are three main types of conditional statements in JavaScript: `if`, `if-else`, `if-else if-else`.

+ if statement: this is used to execute a block of code if a specified condition is checked to be true.
    
--- code ---
---
language: js
filename: script.js
line_numbers: true
---
    if (condition) {
        // Code to be executed if the condition is true
    }
    
--- /code ---

+ if-else statement: this is an extension of the if statement. It allows you to set an alternative block of code to be executed if the initial condition is false.
    
--- code ---
---
language: js
filename: script.js
line_numbers: true
---

    if (condition) {
      // Code to be executed if the condition is true
    } else {
    // Code to be executed if the condition is false
    }
    
--- /code ---

+ if-else if-else statement: this is used when you have multiple conditions to check. It allows you to execute different blocks of code based on the checks.
    

--- code ---
---
language: js
filename: script.js
line_numbers: true
---

  if (condition1) {
    // Code to be executed if condition1 is true
  } else if (condition2) {
    // Code to be executed if condition2 is true
  } else {
    // Code to be executed if none of the conditions is true
  }
    
--- /code ---

+ How to write a conditional statement:
  + The keyword if starts the conditional statement.
  + Inside brackets (), you place the condition that you want to check.
  + If the condition is true, the code inside the curly braces {} is executed.

--- code ---
---
language: js
filename: script.js
line_numbers: true
---

  var age = 18;

  if (age >= 18) {
    console.log("You are an adult.");
}
--- /code ---


