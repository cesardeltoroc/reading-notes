# Programming with java script [CODE 102 Reaod 07]

The **control flow** is the oder in which a computer executes a statements in a script.

A javascript function is executed only when called upon to do so.

A **FUNCTION** is defined by start with **FUNCTION**, it is than followed by an assigned nname, than ending with (parameter1, parameter2, parameter3)
The arguments (**Parameter**) inside the functions act as a local variable to the name function.
The easy way to call upon a function is **assignedName(;)**

When **RETURNING** a function will stop executing.
EXAMPLE:
let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}
The output would be: 12.

Tehe only time you need to assign a variable to a function is when you are returning something inside of a function.

The **RETURN** only returns the information inside of the variable, not the variable itself.

**LOCAL VARIABLES** can only be accessed within a function.

**JAVASCRIPT OPERATORS**

The **Assignment Operator** (=) assigns a value to a variable.
These are all the assignment operators and their signs as follows:

+ Addition

- Subtraction

* Multiplication
** Exponentiation (ES2016)
/ Division
% Modulus (Division Remainder)
++ Increment
-- Decrement

The (+) can also be used to add (concatenate) strings.
Example:
<p id="demo"></p>

<script>
let text1 = "Cesar";
let text2 = "Alex";
let text3 = text1 + " " + text2;
document.getElementById("demo").innerHTML = text3;
</script>

The output would be: Cesar Alex , because the assigned <P Id> has local variables inside.

[Back](README.md)