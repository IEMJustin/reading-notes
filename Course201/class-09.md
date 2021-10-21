# Forms and JS Events

Forms allow for information inputted by a user to be collected to a site. <br>
There are multiple types of forms controls. <br>
A form may also have several form controls. <br>

Form Structure would be made of \<form>, action, id, and method. <br>
The \<form> element should always carry the action attribute. <br>
The action element is also required for the form element. <br>

Some uses for forms would be typing in your username and password. <br>
These forms can also come in the form of a button. <br>
Originally JavaScript was utilized for form validation but HTML5 introduced validation and is allowing the browser to complete the work instead. <br>

## Lists and Tables

List style allows a programmer to express the marker's style. <br>
A table can have many properties. that manipulate the visuals of it. <br>
Some of these properties are listed below:
- width
- padding
- text-transform
- letter spacing, font-size
- border-top, border-bottom
- text-align
- background color
- :hover

The table can manipulate empty cells within the table as well. <br>
The three manipulations would be
- show - Shows border of any empty cells
- hide - Hides the border of any empty cells
- inherit - Inherits the value of another table nested inside

Some common things that are styled in forms would be
- text inputs and text areas
- Submit buttons
- Labels on forms, to get the form controls to align nicely

Text inputs also have the option to be styled by the programmer.
Some of these options are listed below:
- font-size - Changes size of the text entered
- color - Changes the text color
- background-color - Changes the background color of the characters input
- border - Adds a border around the edge of the input box
- border radius - Allows the border to be manipulated further such as rounding the corners
- :focus - Used to change the background color of the text input when used
- background-image - Adds a background image to the box

Even the cursor properties may be manipulated!
Listed below would be the most commonly used property.
- auto
- crosshair
- default
- pointer
- move
- text
- wait
- help
- url("cursor.gif)

## Events

Events allow for certain interactions to activate a script related to it. <br>
There are many types of events that can be utilized. <br>
To utilize an event the element node must be first be selected, along with the script to go with it. <br>
Then the event must be indicated to activate the script. <br>
After that the code that needs to be run would need to be stated. <br>

There are 3 ways to bind an event to an element. <br>
These 3 ways would be HTML Event Handlers, Traditional DOM event handlers, and DOM Level 2 event listeners. <br>
All modern browsers understand the traditional Dom Event Handler but it only allows one function to be attached. <br>
Event Listeners allow more than one function at a time but they are not supported by older browsers. <br>

The flow of events really matter when your code has event handlers on an element and one of its ancestor or descendant elements. <br>

## References

JAVASCRIPT&JQUERY by Jon Duckett
HTML&CSS by Jon Duckett