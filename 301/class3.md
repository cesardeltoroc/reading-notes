# List and Keys

What does .map() return?

Creates a new populated array with new data from a provided function.

If I want to loop through an array and display each value in JSX, how do I do that in React?

Using arrow functions.

Each list item needs a unique ____.

Key vaule.

What is the purpose of a key?

To assign an idtentifier to a element.


# Spread Operator

What is the spread operator?

Allows you to copy all of certian parts of an an array or object to another. 

List 4 things that the spread operator can do.

Combine two objects, combine two arrays, Convert a string into an array and get the maxximum value of an array. 

Give an example of using the spread operator to combine two arrays.

const numbers = [1, 2, 3];

console.log(sum(...numbers));

Would populate >6

Give an example of using the spread operator to add a new item to an array.
<!-- Code Borrowed for Javascripttutorial.net -->
let rgb = [ 'red', 'green', 'blue' ];

let cmyk = ['cyan', 'magenta', 'yellow', 'black'];

let merge = [...rgb, ...cmyk];

console.log(merge);

This will combine the two arrays.

Give an example of using the spread operator to combine two objects into one.

<!-- Code Borrowed for Javascripttutorial.net -->
let employee = {
    ...person,
    ...job
}

# Passing functions between components.

In the video, what is the first step that the developer does to pass functions between components?

Using props to pass functions also passing the function inside of the parent element.

In your own words, what does the increment function do?

It increments a value changes it and returns the value.

How can you pass a method from a parent component into a child component?

Pass the method as a props in the parent to the child element.

How does the child component invoke a method that was passed to it from a parent component?

this.props.METHOD

## Things I want to know more about

Caught up so nothing Im behind on in this subject.
