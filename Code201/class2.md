## Text

The head has 6 levels and the higher in number the headers go the smaller the words become.

A paragraph is enclosed by < p>  This would be a paragraph inside of these tags.< p >

To bold a word simply use **< b >Word< /b >**

To italicize a word simple use ***< i> Word< /i >***

Visual editors can be used to help get a presenataion of how ones code can look.

< strong > between words means the word/ sentence has a meaning and will be bold < /strong>

To quote cite something using a web link you can use the following 
< blockquote cite="LINK">
< P> The food was tasty and I didn't wanna stop eating.< /p>
< /blockquote>

To quote something without using the "" you can use < q> </ q> tags.

To abbrivate an accronym you can use < acronym title="Fast Pizza Place"> Pizza</ acronym>

The < s> < /s> will let you mark a line through information that is not longer valid but you would still like to keep because it may have an importance in the future.

## Introducing CSS

Cascade Style Sheets allow you to design a website and make it look nice.

When wanting to access a specific area use a selector
> p{
  font-family: Arial;
}

The P is the selector and the font-family is the declaration. 

When using internal CSS you can use CSS in html by using style in tags.

A universal selector is *()
A type selector would be like h1, h2 or h3.
A class slector would be .code the name of whatever
A ID selector would be accessed by the #.
A Child selector would be li>a.

## Basic Javascript Instructions

A variable is something that data can be stored inside of Javascript.

You can assign a value to a variable with a assignment operator =.

Storing a number in a variable example 
var price;
price = 5;

Using a variable to store a string example
var people;
people = 'Welcome to the show';

Declating a function can allow you to access multiple variables inside of a function.

## Decisions and Loops

Comparison Operators

== is equal
!= not equal
=== strict equal to
!== strict not equal to
'> > Greater than
< Less than
'>= Greater than or equal too
'>= Less than or equal to

An axample of where compraison operators would be valid is.
var score = 20;
var max = 20;
var comparison = (score == max);

Logical Operators allows you to compare more than one.

&& Logical and
|| Logical or
! Logical not

If statements (checks) if the blocks are **true** than the code block is executed.

if (pizza == 10) {
  console.log('Congrats);
}

This would only execute if the pizza should be 10.

if Else statement is put in place the code will activate if it is false example.

if (pizza == 50){
  console.log('Congrats');
}
else {
  console.log('Hi');
}
[Back](readme.md)
