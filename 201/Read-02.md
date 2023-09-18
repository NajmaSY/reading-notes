# Basics of HTML, CSS & JS

## HTML

https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML

https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals

### Why is it important to use semantic elements in our HTML?

- can be used by search engines and screen readers
- elements give structure, readers can scan page quickly e.g. with clear headings
- SE0 - search engine optimisation - considers key content of web page
- visually impaired - screen reader - listen to pages - easy to read out headings - dont have to listen to all of it
- need elements to style content (CSS) or make it interactive (JavaScript)

### How many levels of headings are there in HTML?

six levels - h1 -> h6
h3> sub-subheadings

### What are some uses for the sup> and sub> elements?

mark up dates, math equations etc...
e.g. 25th - the 'th'

- sup> - superscript
- sub> - subscript

### When using the abbr> element, what attribute must be added to provide the full expansion of the term?

- must use title> - full abbreviation

## CSS

### What are ways we can apply CSS to our HTML?

External stylesheet - .css extension
-can link a single CSS file to multiple web pages - using link> in HTML
Internal stylesheet - in html, use style>
Inline styles - css effecting a single html element

### Why should we avoid using inline styles?

- least efficient - one styling change may require multiple edits within a single webpage
- mixes CSS with HTML and content - more difficult to read and understand
  separating code and content makes maintenance easier for all who work on the website

### Review the block of code below

#### What is representing the selector?

h2

#### Which components are the CSS declarations?

property e.g. font-size + values = declaration

#### Which components are considered properties?

color and padding

h2{
color: black;
padding: 5px;
}

## JS

comment - // or /\* \*/
operator
conditionals - if...else statement
functions - e.g. alert, or define them

### What data type is a sequence of text enclosed in single quote marks?

string

### List 4 types of JavaScript operators.

+, -, \*, /, =, ===, !, !==

### Describe a real world Problem you could solve with a Function.

e.g. search thousands of entries in a database to find a single item
e.g. click "send" button, display message
e.g. lists of cutomers/emails/student info

## Conditionals

### An if statement checks a ** and if it evaluates to \_**, then the code block will execute.

condition -> true

### What is the use of an else if?

more than two choices/outcomes
if, else if, else if, else

### List 3 different types of comparison operators.

===/!==, < >, <= =>

### What is the difference between the logical operator && and ||?

&& - AND - all have to = true
|| - OR - one or more = true

## Git Commit Message

1. communicate context about a change
2. why?
3. up to 50 characters
4. begin with capital letter

## Find out more...

- Description lists
  e.g. terms + definitions, questions + answers
  blockquote>
- address>
- time>
  https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting
