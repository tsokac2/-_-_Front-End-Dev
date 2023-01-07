<h1 align="center">General UI Developer Questions</h1>

### 1. Who is a UI/UX Developer? What did he do?
UI/UX  - User Interface/ User Experience, and the developer has to work for better User Interaction with functionality. The focus is to provide a better interface for a user by front-end coding.

### 2. What skills are required to become a UI Developer?
Human-Computer Interaction, HTML, and CSS along with Photoshop and Graphic Designing are the minimal skills expected from UI Developers, and AngularJS and SEO(Search Engine Optimization) would be preferred.

### 3. What is Semantic HTML?
HTML uses markup that also conveys the containing content. HTML5 has more semantic tags than prior versions (nav | aside | article | header | footer) but uses descriptive classes and IDs could be an example of semantic markup.

### 4. How to call an external style sheet and an external script located in the root folder called ``style.css`` and ``main.js`` with HTML?
```
<script src="main.js"></script>
<link href="style.css" rel="stylesheet"></link>
```

### 5. Name 4 New Elements in HTML5 that were not available in the previous HTML version.

canvas | audio | svg | header | footer | aside | article | nav | section

### 6.  Name 3 attributes of the _position_ property.
static, absolute, fixed, relative

### 7. Name some online resources you reference when having CSS issues.
MDM Docs, Stack Overflow, CSS-Tricks, Reddit

### 8. What is a CSS Reset? What is the difference between a CSS Reset and Normalize.css?
A CSS Reset (or “Reset CSS”) is a short, often compressed (minified) set of CSS rules that reset the styling of all HTML elements to a consistent baseline.
CSS Reset removes browser default styles.
Normalize.css sets a standard across all browsers (It does not 'reset' them).

### 9. How would you solve a floated div's parent height?
Set parent to overflow: auto.
Append a **"spacer"** element inside the parent element

```
.clearfix::after { 
   content: " ";
   display: block; 
   height: 0; 
   clear: both;
}
```

### 10. Declare all elements with the class of "blue-text", to have a text color of blue.
``.blue-text{color: blue;}``

### 11. How do you include a comment in CSS?
``/* This  is a comment in CSS*/``

### 12. Is JavaScript Case Sensitive?
Yes

### 13. What are 2(shorthand) boolean operators supported by JavaScript?

**OR** - `` || ``
**AND** - `` && ``
**NO equal to** - ``!= ``

### 14. what is the difference between "==" and "==="?
``==`` checks equality

``===`` checks equality and type

### 15. What is the result of ``"20" + 20;``?
2020

### 16. What JavaScript Method would convert the string "20" to an integer (on the Fly) so "20" + 20 = 40?
``parseInt("20") + 20;``

### 17. What is an AJAX request and what is a simple example of where an AJAX request would be used?

**AJAX** - Asynchronous JavaScript and XML. 

The client-side process is used for GET, POST, etc to get new data without having to refresh the page.

### 18. Assign any variable name a value of "hello World" and print that variable contents to the console.
```
var t = "Hello World";
console.log(t);
```

### 19. Create an array in JavaScript with a list of 4 colors, and assign that array to the variable "colors"?

``var colors = ['red', 'yellow', 'green', 'blue'];``

### 20. How do you include a Comment in JavaScript?
```
// This is a single comment line
/* This is a comment block */
```

### 21. Loop through the color array and print each value to the console. Assume you do not know the number of colors in the color array.
```
var colors = ['red', 'yellow', 'green', 'blue'];
for( var i = 0; i <= colors.length; i++){
	console.log([i]);
}
```
### 22. What is jQuery?
A JavaScript Framework/Library that makes things like DOM selections/manipulations, AJAX, and animation easier to code.

### 23. What programming language does jQuery use?
JavaScript

### 24. Is jQuery executed on the Clientside or Serverside?
Clientside

### 25. How do you install/use jQuery in a project? What is the minimum setup needed to start using jQuery?
script tag - linked to a jQuery CDN or locally hosted file.