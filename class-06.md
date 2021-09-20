## Objects Literals and The DOM

### Object literals
If a variable is part of an object, it is called a property and if a function is part of an object, it is called a method. <br>
Literal notation is the easiest and most popular way to create objects. <br>
You can also properties or methods of an object using dot notation or with square brackets. <br>

### The DOM

The DOM specifies how browsers should create a model of an HTML page and how Javascript can update the contents of a webpage while it is in the browser. <br>
People may refer to the DOM as an API. <br>

### The DOM Tree

There are two steps for accessing and updating the DOM Tree. <br>
The first step would be locating the node that represents the targeted element. <br>
The second step would be using it's attributes, text, and child elements. <br>

The two example for selecting an individual element would be getElementById and querySelector. <br>
Methods for selecting multiple elements would be getElementsByClassName, getElementByTagName, and querySelectorAll. <br>

When working with an element more than once it should stored by using a variable. <br>
Elements can be selected by using ID Attributes. <br>

A NodeList is a collection of element nodes. <br>
Each node is given an index number, similar to arrays starting at 0. <br>
The two ways to select an element from a NodeList would be the item() method and array syntax. <br>
Both methods require the index number of the element you want. <br>

> var element = document.getElementByClassName('hot') <br>
> if (elements.length >= 1) { <br>
>   var firstItem = elements.item(0); <br>
} <br>

> var element = document.getElementsByClassName('hot'); <br>
> if (elements.length >= 1) { <br>
>    var firstItem = elements[0]; <br>
} <br>

When a NodeList is present you can loop through each node within the collection and apply the same statements to each. <br>
Traversing the DOM consists of selecting an element in relation to another element and using these five properties below: <br>
- parentNode
- previousSibling
- nextSibling
- firstChild
- lastChild

Some difficulties that may present themselves while traversing the DOM would be browsers adding a text node when they come across whitespace between elements. <br>
When a text node is selected a user can retrieve or amend the content using the nodeValue property. <br>
DOM manipulation targets individual nodes in the DOM tree while innerHTML is better used for entire fragments. <br>

If you add HTML to a page with innerHTML you need to be aware of Cross-Site Scripting Attacks or XSS. <br>
Allowing users to only type in characters they need to when supplying information assists in protecting your site. <br>

## References
- JAVASCIPT & JQUERY by Jon Duckett