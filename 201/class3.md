## List
> An <ol> is and ordered list.

This will make the listed items have numbers next to them.

> The <li> tag is usually the list items inside the ordered list.

> An <ul> is an unordered list.

This will put a bullet point next to the listed items.

Definiton list usually has a term and the definition of the term
> <dl>

> <dt> Is used to define the term being defined

> <dd> Is used to define the term being presented in the <dt> tag.

An axample would be:

> <dl>

>  <dt>Fruit<dt>

>   <dd> Something that is edible and tasty<dd>

> <dl>

> Nested listing is simply putting a <ul>  and </ul> inside a <li> to create subitems.

### Boxes

If the content overflows you can ass a scroll box by using 

overflow: scroll;

The border on a box covers the lettering

The margin on a box is the outside of the edges.

The padding is the space between the border of a box. <!-- HTML & CSS By:John Duckett -->

You can adjust the bordewr width with the command in css

p {

  border-width: 2px;
  
  }

There are also different style in borders in css that can be accessed on VSCODE w autofill.

To change a border color simply use this in css

p {

  border-color:white;

}

To change all sides of the border simply pick 4 different color and it will go in clockwise order. 

The padding allows you to space the content in an element within it's border.

Margins are spaces between different borders that have content inside of them. 

To allign content you can use 

text-allign: center;

Changing  

inline: puts listed items in line

block: creates blocks around whatever the content is

inline-block: listed items will be put in line inside of borders.

none: no style

> To hide a <li> simply assign the li using <li class="text"> Example </li>

Than access the class in CSS by doing 

li.text {

  visibility:hidden;

}

Rounded corners in CSS for borders

p { 
  
  border: 5px solid red;

-moz-border-raduis: 10px;

-webkit-border-raduis: 10px;
}

[Back](README.md)
