# HTML Links, JS Functions, and Intro to CSS Layout

### Functions, Methods, and Objects
Functions, Methods, and Objects allow for a programmer to organize trheir code. <br>
Functions consist of a series of statements that have been grouped together to perform a specific task. <br>
Methods are similar to functions but they are created inside an object. <br>
Objects are made up of properties and methods. <br>

### Links
Links allow for a fluid web-surfing experience by allowing the user a direct path to another url through a single click. <br>
Links have multiple ways of being used whether they direct the user to a new window or sends the user to the url within the same tab. <br>
Links are created using the \<a>urlgoeshere\</a> element.
Anything within that element is clickable. <br>

### Link Examples

> Link to other site
> \<ul> <br>
> \<li>\<a href="https://www.codefellows.org/"> <br>
>    CodeFellows\</a>\</li> <br>
> </ul> <br>

Link to other pages on the same site
> \<ul> <br>
> \<li>\<a href="index.html">Home\</a>\</li> <br>
> \</ul> <br>

### Directory Structure

When operating on a larger website it is good practice to organize code by placing the pages for each different section of the site into a new folder. <br>
These folders are also known as directories. <br>
The main homepage of a site written in HTML is called index.html. <br>
The relationship between files and folders are similar to that of a "family tree". <br>

### Utilizing Links

Programmers also have the ability to further customize how the link will react when activated. <br>
A link can be manipulated to send a user to a specific part of the page when selected. <br>
This option for customization link behavior would apply to a link being on the same page and a whole new separate url. <br>

### Layout

### Controlling the position of elements
The key concepts for positioning elements would be Block-Level elements, Inline elements, containing elements, and Block level boxes. <br>
CSS will treat each HTML element as if it was isolated in it's own box. <br>
If one block-level element sitting inside another the outside block-level element is considered as the containing or parent element. <br>
A multitude of floats may also be utilized to position boxes in specific areas within the page as well. <br>


### Screen Sizes, Screen Resolution, and Page Sizes
Visitors to the sites will have many different sized screens, so the programmer must adapt the website to accomodate for those conditions. <br>
Screen Resolution refers to the number of dots a screen shows per inch. <br>
To accomodate the many different screen sizes of users, designers will try to create a page that is around 960-1000 pixels wide. <br>

### Layouts

Fixed layout designs do not change size as the user incrases or decreases the size of their browser. <br>
#### Benefits of Fixed Width Layouts

- Pixel value are accurate at controlling size and positon of elements
- More flexibility with control over appearance
- Control over length of text lines
- Size of images won't be distorted and stay static
#### Disadvantages of Fixed Width Layouts

- Possibility of big gaps on page
- Higher resolution screens may look smaller and text can be hard to read
- Page will usually take up more vertical space than liquid layout

Liquid layouts allow the page to stretch and contract based on the size of the browser. <br>

#### Advantages of Liquid Layouts

- Pages able to exapnd and fill the entire browser.
- Users with a smaller window might have issues
- Design is tolerant of users personal settings

#### Disadvantages of Liquid Layouts

- Does not control width of the sections
- Words can become hard
- Images may overflow over text