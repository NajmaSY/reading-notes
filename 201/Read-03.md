# class-03

## HTML lists, Control Flow with JS, and the CSS Box Model

- array
- index
- true or false
- control flow-make things work in order
- loop - repeats itselft
- iteration - each individual time code repeats

## HTML - Lists

Ordered - using ol> then li>
unordered - use ul> then li>

### When should you use an unordered list in your HTML document?

- bullet points in no particular order like a shopping list
- to improve readability of code
- not relevant items but are related to eachother

### How do you change the bullet style of unordered list items?

- list-style-type: circle/disc/square (CSS)

### When should you use an ordered list vs an unorder list in your HTML document?

- when the order is important e.g. recipes,

### Describe two ways you can change the numbers on list items provided by an ordered list?

- can use roman numeral i. ii. iii.
  ol> type="i" or type="a" - for lower case

## CSS - The Box Model

- everything in CSS has a box around it.
- use display property
- block = box breaks into a new line
  use height and width in CSS file
- inline - padding, margins, borders apply

### Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

sets all four sides of a box
margin - separates box from other elements
top, right, bottom, left
padding - between border and content. cannot be negative,

### List and describe the four parts of an HTML elements box as referred to by the box model.

content box - content area - size it using width and height
padding box - around the content
border box - wraps the content and padding
margin box - outermost layer

## JS - Arrays, Operatos and Expressions. Conditionals. Loops

arrays - store lsit of data items under a variable

### What data types can you store inside of an Array?

string, numbers, objects, other arrays,can have a mix of data types

### Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

- can store multiple data types and other arrays in a single array
- can use console.log(people;
  can add or remove from the array

const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

### List five shorthand operators for assignment in javascript and describe what they do.

= -> stores a value in a variable
+= ->additon
-= -> subtraction
\*= ->multiply
/= ->division

### Read the code below and evaluate the last expression and explain what the result would be and why.

let a = 10;
let b = 'dog';
let c = false;

// evaluate this
(a + c) + b;

- 10falsedog

### Describe a real world example of when a conditional statement should be used in a JavaScript program.

e.g. weather app - morning-show sunrise etc
e.g. game - plsyer's number of lives =0 then game over

### Give an example of when a Loop is useful in JavaScript.

for repetitve tasks
calculations
