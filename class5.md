# Structuring with CSS [CODE 102 Read 05]
CSS (Cascading Style Sheets) allows the creation of a nice looking website.

Usually CSS is used to make a HTML document look nicer.

CSS is a rule based language here is an example: 
h1 {
    color: red;
    font-size: 5em;
}

changing color is "color: green:" without the apos.

changing font in CSS is as "font-size: 4em;" without the apos also.

To use CSS in HTML create a folder in your HTML file and save it as **style.css**
And to link the style with the HTML put this code inside of the HEAD of the HTML file. 
< link rel="stylesheet" href="styles.css" > without the spaces inside.

To target all paragraphs in HTML with CSS use 
p {
  color: green;
}

When trying to pick a specific work or lines ise this and repalce "em" if another phrase is active.
li em {
  color: rebeccapurple;
}

This is a great command to change background color on CSS 
body {
  background-color: lightblue;
}

This command will make the following < P > in the situation blue writting and a green background.
p {
    color: blue;
    background-color: green;
}

When lost you can use this to access Style Syntax rule
style-rule ::=
    selectors-list {
      properties-list
    }




[Back](README.md)