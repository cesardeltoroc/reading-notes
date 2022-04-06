# Read 12

In your own words, describe what each group of status code represents:

100’s = They give the user information as the where the header went wrong.

200’s = Successful status codes.

300’s = Status code that lets the user know that the link might've been redirected.

400’s = Client error, user sending improper data to the server.

500’s = Something is wrong with the server not the user end.

What is a status code 202?

The request has been accepted, but has not yet been processed.

What is a status code 308?

Indicates that the URI has been changed to another location. 

What code would you use if an update didn’t return data to a client?

The status code that would populate is a 404.

What code would you use if a resource used to exist but no longer does?

You could also use a code 404.

What is the ‘Forbidden’ status code?

403, means that the server understood the code but reject's it.

# Reading 12 Part 2.

Why do we need to pull our MongoDB database string out of our server and put it into our .env?

So our server can find where what database to pull form for information.

What is middleware?

Middleware is what 'glues' together software's. Middleware enables communication and data management for distributed applications. - Microsoft

What does app.use(express.json()) do?

It parses incoming JSON request and puts them in a req.body.

What does the /:id mean in a route?

It's a query parameter that allows you to access whatever the user types in on the front end in the back end. 

What is the difference between PUT and PATCH?

PUT places the data and modifies the entire source, while PATCH just adds to exsisting data.

How do you make a default value in a schema?

const Schema = new Schema ({
  name:{
    name: string,
    age: num,
    desc: string
  }
})

What does a 500 error status code mean?

SERVER ERROR!!

What is the difference between a status 200 and a status 201?

200 means that it was recieved and hasn't given an response yet, while 201 indicates that a request was successful which leads to a resource being created.

## Things I want to know more about

How to work with Regex more, not corresponding but that's what I am focused on currently.
