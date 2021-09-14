# BASICS OF HTML, CSS & JS

### JavaScript

#### Statements

A script is a series of instructions that tell a computer what to do.
Every individual instruction is known as a statement.
When utilizing JavaScript, everything is CASE SENSITIVE.
Everyone statement would begin on a new line.

***

#### Comments

Comments are a way to describe what the code is doing.
It will assist with making the code easier to read.
When utilizing single-line comments using the characters // will allow for the characters following to not be processed by the JavaScript interpreter.
But to utilize multi-line comments a user ,must start with /* and end with /*

***

#### Variables

A variable is a temporary container for the information that is produced from the script.
Before utilizing the variable a user must declare the variable.
JavaScript will recognize the value between 3 data types.
Booleans can only be true or false values.
The data types recognized are:
- Numeric Data Type
- String Data Type
- Boolean Data Type

Examples Below

> var example;

> var 7;

> var example; <br>
> example = true;

***
#### JavaScript

> var price; <br>
> quantity; <br>
> total; <br>
> <br>
> price = 5; <br>
> quantity = 14; <br>
> total = price * quantity; <br>
> <br>
> var endtotal = document.getElementById('cost'); <br>
> endtotal.textContent = '$' + total; <br>

***

Only after declaring a value a programmer can then assign a value.

> var example = 777

> var example = newexample

When storing a variable in a string the user must be uniform when applying quotation marks.
For example, if the user begins with double quotes they must use double quotes at the end as well.
If a user uses single quotes they must use single quotes at the end as well.

> "correct"

> 'correct'

> "wrong'

> 'wrong"

***

Programmers will also sometimes use shorthand to create variables.

> var price = 5; <br>
> var quantity =14; <br>
> var total = price * quantity; <br>

When attempting to change the value of a variable the user no longer needs to use var.
Instead the user would use the variable's name.
The code would consist of the variable's name, the = sign, followed by the new value for the variable.

#### Rules for Naming Variables

- The name must begin with a letter,dollar sign, or an underscore.<br>
It CANNOT start with a number.
- The name can contain letters,numbers,dollar sign, or an understore.
A dash or a period cannot be utilized.
- Keywords or Reserved words cannot be utilized such as prompt.
- All variables are case sensitive.
- Use a name that describes the kind of information that the variable is storing.
- If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word
> planetHollywood

### Arrays

Arrays store a special type of variable.
It will store multiple values within it.
The techniques for creating a variable are array literal and array constructor.
Values in an array are accessed as if they were in a numbered list.
The numbering of the lists would start at zero and not one.
To access and change values within an array you must specify the index number for the value after the array name.

Expressions evaluate into a single value.
There would be two types of expressions.
Expressions that assign a value to a variable.
The other type would be expressions that use two or more values to return a single value.

### Decisions and Loop

Codes can take more than one path depending on the situation at hand.
A flow chart can assist with visual represenation for brainstorming before attempting to execute the script.
Within a script there are multiple areas where decisions are being made.
These decisions would determine which line of code would be ran next.

There are two components to a decision.
- An expression is evaluated, which returns a value
- A conditional statement that says what to do for a specific situation

There are multiple operators for comparison and evaluating.
In any condition, there is usually one operator and two operands. Both operands are placed on the ends of the operator. 
They can be values or variables.
The expressions are normally enclosed within parentheses.

At the basic level, two variables can be evaluated by utilizing a comparison operator to return a true or false value.
Logical Operators can be thrown into the mix of things as well.
Logical Operators allow you to compare the results of more than one comparison operator.

### IF STATEMENTS

IF Statements evaluates a condition.
If the condition is met, any statements following in the subsequent code block would be executed.

### TEXT

When creating a webpage, tags that are added within the content would also be known as markup.
These tags provide extra meaning and allow browsers to display the intended structure for the page.

### Structual Markup

The elements that you can use to describe both headings and paragraphs.

### Semantic Markup

Provides extra information, such as where emphasis is placed in a sentence.

Headings have 6 levels, they are h1,h2,h3,h4,h5, and h6
They are enclosed within pointy brackets facing outward.
Paragraphs are surrounded by the p character enclosed by pointy brackets facing outwards as well.

Web page authors would often add extra spaces on new lines to make code easier to read.
If there is more than one space, the browser would display only one space.
Line breaks are utilized to make a line end and any text after would start on a new line.
Horizontal rules are added to begin a new section and separate them with a line.

### Visual Editors

Visual Editors normally resemble word processors.
Although editors may be similar they have slight differences.
This would be due to dofferent features they may have.

### Semantic Markup

There are some text elements that are not intended to affect the structure of webpages.
Semantic Markup instead adds extra information to the pages.
Some examples that you may run into would be strong & emphasis, quotations, abbreviations & acronyms, & dictations & definitions.

### CSS

CSS will allow for further development of the "beautification" regarding the webpage.
CSS allows you to create rules that would control the visuals of each individual section.
CSS associates rules with HTML elements to execute.
CSS declarations would sit within curly brackets and each is made up of two parts.

Property and Value which are separated by a colon make up a declaration in CSS.
It is possible to specify several properties within one declaration.
CSS can be used externally and internally.

To utilize CSS externally you would need 3 components.
The three components would be href, type, and rel.
Href would specify the path to the CSS file.
Type would be text or css and specifies the document type that it's being linked to.
Rel would specify the relationship between the HTML page and the file it is being linked to.

To utilize CSS internally you would be utilizing the style element.
The style element should specify text/css.
When attempting to build a site with more than one page, you should utilize an external style sheet instead of internal.

CSS Selectors are used to target rules for specific elements in an HTML document.
CSS Selectors are case sensitive.
More advanced selectors are available that would allow one to slect elements base don attributes and their values.

If there is more than one rule with the same element CSS will cascade.
This means that the last selector would take priority over the ones prior to it due to it being the last selector being processed.
CSS also has the ability to make child elements inherit propertiess.