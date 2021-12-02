## Javascript Notes

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
 }
 
 [Back](/README.md)
