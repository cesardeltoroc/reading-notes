# These are notes for Operations and Loops [Code 102 Read 08]

These are all JavaScript operators:
Assignment operators
Comparison operators
Arithmetic operators
Bitwise operators
Logical operators
String operators
Conditional (ternary) operator
Comma operator
Unary operators
Relational operators


**Assignment Operators:**             Smoothand Operator:       Meaning : 
Assignment	                             x = y	            x = y

Addition assignment	                     x += y	            x = x + y

Subtraction assignment	                 x -= y	            x = x - y

Multiplication assignment	             x *= y	            x = x * y

Division assignment	                     x /= y	            x = x / y

Remainder assignment	                 x %= y	            x = x % y

Exponentiation assignment	             x **= y	        x = x ** y

Left shift assignment	                 x <<= y	        x = x << y

Right shift assignment	                 x >>= y	        x = x >> y

Unsigned right shift assignment	         x >>>= y	        x = x >>> y

Bitwise AND assignment	                 x &= y	            x = x & y

Bitwise XOR assignment	                 x ^= y	            x = x ^ y

Bitwise OR assignment	                 x |= y	            x = x | y

Logical AND assignment	                 x &&= y	        x && (x = y)

Logical OR assignment	                 x ||= y	        x || (x = y)

Logical nullish assignment	             x ??= y	        x ?? (x = y)]

An **ASSIGNMENT OPERATOR** assigns it's value to its left operand based on the value of its right operand. The simple assignment operator is **(=)**.
For example: say x = y itll than assign the value of y to x.

When chaining these expressions, each assignment is evaluated right-to-left.

For more complex assignments, the destructuring assignment syntax is a JavaScript expression that makes it possible to extract data from arrays or objects using a syntax that mirrors the construction of array and object literals.
For Example: 
var me = [ 'one', 'two', 'three' ];
//without deconstructing
var one   = me[0];
var two   = me[1];
var three = me[2];
//with deconstructing 
var (one. two, three) = foo;

**COMPARISON OPERATORS**
Equal (==)	                Only remainds true if the opreands are equal.

Not equal (!=)	            Returns true if the operands are not equal.	

Strict equal (===)	        Returns true if the operands are equal and of the same type. See also Object.is and 
sameness in JS.	

Strict not equal (!==)	    Returns true if the operands are of the same type but not equal, or are of different type.	

Greater than (>)	        Returns true if the left operand is greater than the right operand.	

Greater than or equal (>=)	Returns true if the left operand is greater than or equal to the right operand.	

Less than (<)               Returns true if the left operand is less than the right operand.	

Less than or equal (<=)     Returns true if the left operand is less than or equal to the right operand.	

A **FOR LOOOP** is good when you know how many times you want something to execute. Theyre typically used with arrays.

for (let i = 0; i <=12; i = i + 1){

    console.log (i * 8);

}
This loop would run 12 times.

While Loop


Link to website: 
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration

[Back](https://cesardeltoroc.github.io/reading-notes/)
