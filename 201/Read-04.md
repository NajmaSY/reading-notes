# HTML Links, JS Functions, and Intro to CSS Layout

## HTML - creating hyperlinks

### To create a basic link, we wrap text or other content inside what element?

- we wrap the text inside an a> element using href=

### The href attribute contains what information?

- web address

### What are some ways we can ensure links on our pages are accessible to all readers?

- clear link wording - involve the context of the link in the name, search engines use link as keywords to index target files, visual reader skim the page so their eyes will be drawn to features that standout so use a descriptive link

## CSS - Positioning

### What is meant by “normal flow”?

- the way webpage elements lay themselves out if you havent changed their layout
- when css hasnt been applied yet
- readable normal flow

### What are a few differences between block-level and inline elements?

- by default, a **block level** element'c content fill the available inline space of the parent element containing it, growing along the block dimension to accomodate its content. each element appear on a new line.
- the size of an **inline-level element** is just the size of thei content. set width and height on some elements that have a default display property of inline, like img, the the display will still remain inline. sit on the same line with text content

### Static positioning is the default for every html element.

### Name a few advantages to using absolute positioning on an element.

- sits on it own layer separate from everything else
- we can create isolated UI features that dont interfere with the layout of other elements on the page, e.g. popup boxes, control menus, rollover panels - can be dragged and droppesd anywhere on the page

### What is a key difference between fixed positioning and absolute positioning?

- absolute positioning fixes an element in place relative to its nearest positioned ancestor, whereas fixed positioning usually fixes an element in place relative to the visible portion of the viewpoint

## JS Functions - reusable blocks of code

### Describe the difference between a function declaration and a function invocation.

functions allow you to store a piece of code that does a single task inside a defined block, and then call that code whenever you need it using a single short command

- function declaration - creating a function
- function invocation - after its been defined, run/invoke the function

### What is the difference between a parameter and an argument?

- parameter - values that are included inside the function parentheses
- argument -

## Benefits of Pair Programming

- when two people focus on the same code base, its easier to catch mistakes - more efficient
- code become higher quality
- become more focused when working in a group, can rely on the other when there a bug
- learn from them - a different approach/technique to a specific problem i can adapt
