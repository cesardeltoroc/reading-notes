<!-- ## Javascript Notes

An **Array** is a description of an element ( it can be numbers or letters ), They have [EXAMPLE] stuff inside. A collection of elements or a list of items. It can hold more than one value and other **arrays** and **objects**.

**Arrays** have indexes         0        1       2       3
>       Index: let student = ['Josh', 'Kevin', 'Rob', 'Cesar'];

> To console.log(student[2]);

Sub Array examples: 
>    let mixedArr = [1, 'hello', true, [2, 3]]

Accessing the **Sub Array in this above**

console.log(mixedArr[3][1]);

Checking the length of an **Array**

console.log(students.length)

undefined: Flase
null: False

Adding things to the array goes ass follows

students[4] = 'Micheal", Would add miachel to the already existing array.

Adds an element to the end of the array.

student.push('Shane;);

## DIVS
> A <div></div> tag allows you to create a box around the content inside of it.

You can style the div in css by using an element selector. 

If a div is placed inside of a header or another section do not assign a height because if the content exceeds the high set in CSS it may leave the header.

Whenever centering **DIV** tags it'd be easiest using **margin: auto;** in CSS.


## For Loops

A for loop can be using for doing something a certain ammount of times.

        Declaring variable;     accessing an array;    increments of 1

> for(   let i  =  0;          i < students.length;    i++   ){
      
      
      
      console.log('Welcome Class' + students[i] + "!")
              
          String contatination +  accessing the array start at 0 + string contatination.
}


## While loops

let weAreDoneHere = false;

let attempts = 4;

let idexCount= 0;

> while(!weAreDoneHere){

  console.log('Welcome to class ${student[IndexCount]} !');
  
  indexCount++;
  
  attempts--;
  
  > if (!attempts){
  
    weAreDoneHere = true;
  
    console.log('we are done!');
  
      }
 } -->

## Links

Links are created by opening with an anchor tag.

> < a href="link">Title< /a> 

The user would click the Title and it will take them to the link provided inside of the opening tag link.


Linking to other pages on the same site would just change the URL to the file name of the page your trying to access on the same page.

> < a href="cookie.html">Cookies< /a>

If you want a URL link to open in a new window in html use the same for but insert target blank example:

> < a href="Link" target'= "_blank'> Traget< /a>(Opens in new window)'.

## Layout

Floating elements can move from left or right moving the elements inside.

Some floats may carry on to other elements in the webpage so if that arises simple .clear in CSS
> .clear {
  clear: left;
}

Using class names in HTML can make it easiert to navigate when using CSS in css frameworks to make the website easier to design.

## Functions

A basic function can store data inside of it by stoing multiple statments.

 Declaring a function goes as follows
> function helloWorld(){
> document.write('Hello World');
> }
 
 To call that function above you could use a script tag in HTML or simply insert in Javascript
 >helloWorld();

 Delclaring a function that needs information inside, inside of the () parameters are stored.
 > function getSize (width, height){
 >  return width* height;
 > }

 In a function declaration you must invoke the function somewhere in the code for it to work.

## Pair programming

Pairing when programing can help with one's social skills and create a sense of a work environment.



 [Back](https://cesardeltoroc.github.io/reading-notes/)
