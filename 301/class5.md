# Thinking in React

What is the single responsibility principle and how does it apply to components?

Usually has only one job. Which means it should only have one reason to change. 

What does it mean to build a ‘static’ version of your application?

Non reliant on databases or online servers.

Once you have a static application, what do you need to add?

A server or datebase.

What are the three questions you can ask to determine if something is state?

How the data is being stored?
Is it being stored somewhere you need to pass it to another component.
Why cant this be accessed in a certain file eventhough it's global?

How can you identify where state needs to live?

You can determine where the data needs to be accessed and place it in that file.

# High Order Functions

What is a “higher-order function”?

A function that operates on another function by using them as arguments or returning them.

Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

It's returning the value of a parameter being accessed by another function snd reuturning the value.

Explain how either map or reduce operates, with regards to higher-order functions.

They operate almost the same they just take in another function.
