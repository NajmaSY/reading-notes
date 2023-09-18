# Class 01: Setup Developer Toolbelt
## Getting started with the web
plan the code for your website
- whats it about?
- what info are you presenting on the subject - title/paragraphs/images
- what does the website look like? - background color/font
- sketch using OkSo
- theme color scheme - color picker
- google images
- font - reference from google fonts

## How the web works?
when you view a webpage in web browser on computer/phone
- clients/servers - clients are the internet connected devices e.g. computer with WiFi/phone or FireFox or Chrome. servers - coputer
- link - browsers send requests to servers for HTML files, reference CSS or script to ref JS
- data sent in packets - faster/download at same time

## until "Comments" section
**How HTTP sends data between computers.**
- hypertext transfer protocol - defines a language for clients and servers to speak to eachother.
- browser -> DNS server ->finds address of server where website lives on
- browsers sends HTTP request message to server - send copy of web to client
- sent across internet connection
- server approves? -> sends website's files to browser in "packets"
- browser assembles chunks of data into a complete webpage and displays it to you

**Describe how HTML, CSS, and JS files are “parsed” in the browser.**
- when browser sends requests to server for HTML files, these contain link or script
- browser parses HTML first, recognises link for CSS and script
- browser sends back requests to server for CSS files its found from link elements and JavaScript, it then parses CSS and JS
- browser generates an in-memory DOM tree from parsed HTML, makes in-memory CSSOM structure from the parsed CSS, compiles and executes the parsed JS
- as browser builds DOM tree and applies styles from CSSOM tree and executes JS, a visual representation of the page is painted to the screen, user sees page content and can begin to interact with it

**How can you find images to add to a Website?**
google images

**How do you create a String vs a Number in JavaScript?**
string - quotes ' ', " "
let name = 'najma';
number - e.g. let score = 1;

**What is a Variable and why are they important in JavaScript?**
variables stores a value/result of an operation
it can be changed anytime and used later on in code

## Intro to HTML
- header 
- nav bar - links 
- main -  article, section, div
- sidebar - aside tag inside main
- footer- 

**What is an HTML attribute?**

**What is the Difference between <article> and <section> element tags?**
- article - block of related content that makes sense on its own without the rest of the page e.g. a single blog post
- section - groups together a single part of the page that has one function e.g. mini map, set of article headlines and summaries, a theme
- begin each section with a heading, you can break article into different sections/sections into different articles depends on context

**How does metadata influence Search Engine Optimization?**
specifying a description that includes key words rekating to the content of you page - higher in relevant searches

**How is the <meta> HTML tag used when specifying metadata?**

metadata - data that describes data included in head in HTML
name= and content=

## Miscellaneous
**What is the first step to designing a Website?**
- ideas - structure it/goals/list
- turn into actionable steps
- what features to implement - broad steps not always web related

**What is the most important question to answer when designing a Website?**
what do i want to accomplish
how will it help me reach my goals
what needs to be done, in what order to reach goals

**Semantics**
Why should you use an h1 element over a span element to display a top level heading?
span - no semantic value or added benefits (large font size by default)

What are the benefits of using semantic tags in our HTML?
- search engines will consider its contents as important keywords
- readers can signpost - help visually impaired navigate a page
- easier finding blocks of meaningful code than seraching through endless divs with/without semantic classes
- suggests to developer types of data that will be populated - less emphasis on styling

**JavaScript**
Describe 2 things that require JavaScript in the Browser? 
HTML and CSS

How can you add JavaScript to an HTML document?
script in html 
inline code

## Things i want to know more
- parsed
- input images/video/audio - easier way to do it
- anatomy of HTML - structure