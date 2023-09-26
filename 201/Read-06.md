# Problem Domain, Objects, and the DOM

## JavaScript Object Basics

object syntax

### How would you describe an object to a non-technical friend you grew up with?

- collection of related data and/or funcctionality
  e.g. variables and functions
- create object -- define/initialise variable
- e.g const person = []
  in terminal enter person

### What are some advantages to creating object literals?

- shorter syntax
- sending a request with a single object is easier

### How do objects differ from arrays?

### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

person.age; -> person ['age' ;

### this.

- current object the code is being written inside
- useful when creating more than one object literal

## The DOM

### What is the DOM?

- Document Object Model
- a Web API used to build websites
- data representation of the objects that comprise the structure and content of a document on the web
- represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.
- A web page is a document that can be either displayed in the browser window or as the HTML source. In both cases, it is the same document but the Document Object Model (DOM) representation allows it to be manipulated.

### Briefly describe the relationship between the DOM and JavaScript.

- As an object-oriented representation of the web page, it can be modified with a scripting language such as JavaScript.
- the browser downloads the HTML along with any referenced JS and CSS (and images, Flash etc.). The browser constructs the DOM from the HTML and renders it using the rules specified in the CSS. JS may manipulate the DOM when the page loads, when the user does something, or when any other event happens. When the DOM changes the browser updates what is displayed.
- it is written in JavaScript, but uses the DOM to access the document and its elements

## What’s the difference between primitive values and object references in JavaScript?

### data types

Boolean
Null
Undefined
Number
BigInt
String
Symbol
Objects
