# Read 01








## Class Notes

> FS: File System library in node.

> 'use strict' : enforces strict variable naming conventions.

### Node Modules
> All node modules will have a package.json file.

> Traits: shearable(module), installed by the npm [or you can publish yourself], includes a package.json, it can import and export (programs / code).

> In Node. js, Modules are the blocks of encapsulated code that communicates with an eternal application on the basis of their related functionality. Modules can be a single file or a collection of multiples files/folders.

> Node.js is an open-source, cross-platform, back-end JavaScript runtime environment that runs on a JavaScript Engine and executes JavaScript code outside a web browser, which was designed to build scalable network applications. 

## Creating a package.json / server
 1. npm init
 2. package name: module_name
 3. version: v1
 4. description: HAPPY FILE
 5. entry point (index.js): index.js
   
> Import a module

requires IS  a built in function in javascript. 

> Exporting a module

> There are many ways to do so but this is also a way.
- module.exports = (a, b) => {
    return a + b;
}

> Importing a file w/ requires.

> const main = require('./index.js)

> Express

> Request: 
- app.get(‘/’, function (req, res) { })  
- QUERY PARAMS (/query?name='CESAR'&role='STUDENT') passing in the backend looking for a value in both of the QUERY's being sent in.
- URL or Path. (www.website(/hello))- Methods: PUT/ GET/ POST/ DELETE

> Respone:
- Object{}

# White Board (example)
> Reverse an array in place, in place means keeping the same array and not creating a new array.

> Input [1, 2, 3, 4, 5, 6]

> Output [6, 5, 4, 3, 2, 1]

> 

