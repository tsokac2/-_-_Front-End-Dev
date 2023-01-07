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

### 26. How do you select all elements with the class of ``.selected`` in jQuery?
``$('.selected');``

### 27. Can jQuery be used to make an AJAX Request?
Yes

### 28. What is the difference between ``Require()`` and ``Include()`` when an error is encountered?
``include()`` will raise a warning if it fails, ``require()`` will raise a fatal error.

### 29. What is the current major version of Bootstrap?
v5.0 is the latest version - [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/)

### 30. What CSS class do you use to span 12 columns on medium-sized screens but only 6 columns on large screens in the latest version of Bootstrap?
``class="col-md-12 col-lg-6"``

### 31. Name 3 available jQuery plugins that Bootstrap has in their Query Plugin Library.
Modal, Carousel, Tooltip, Dropdown, Alert, Collapse

### 32. What minimum things do you have to do to include Bootstrap and Bootstrap JS in a project HTML Document?
Add ``bootstrap.css/bootstrap.js`` link and script in the head of the HTML document.

**NOTE** If ``bootstrap.js`` script is included in the footer (better for page loading)

### 33. What is the difference between ``xhtml``, ``html4`` and ``html5``. Which do you use typically?
**XHTML** was the cleaner and stricter version of HTML4.

**HTML5** is the latest, smartest, and fastest version of HTML.

### 34. Does HTML need a compiler?
**HTML**, **CSS**, and **JS** are browsers-interpreted technologies.
Whereas ``asp.net``, ``java`` and ``PHP`` are not interpreted.

They need a compiler that can convert their code into machine language.
That's why HTML, CSS, and JavaScript are also called front-end technologies.

### 35. What is Semantic HTML?
HTML5 introduced semantic tags like ``header``, ``nav``, ``article``, ``section``, ``aside``, ``footer`` and ``figcaption``.

These tags convey the containing content.
Whereas in html4, the div tag was used to create partitions using descriptive classes.

### 34. Which is the best HTML debugging tool?
We use **Chrome**, **Firefox**, and **Firebug Devtools** as they are browser inbuilt.

But W3C Validation is the best HTML Debugging tool.

### 35. How to use HTML5 new tag in IE8 and lesser?
HTML5 semantic tags like ``header``, ``nav``, ``article``, ``section``, ``aside``, ``footer`` and ``figcaption`` are not supported in HTML4 based browser like IE8 and lesser.

We can use ``html5shiv.js`` to run these elements in older browsers.
[html5shiv CDN](https://cdnjs.com/libraries/html5shiv)

### 36. What is web accessibility?
Web accessibility means a web for differently-abled or disabled people.
HTML5 introduced WAI-ARIA so that even disabled people can interact, understand, and navigate a website.
[WAI-ARIA](https://www.w3.org/TR/wai-aria-1.2/)

### 37. Difference between ``<b>`` and ``<strong>`` tag?
``<b>`` is a presentational element used to give bolder look to the text.

Whereas ``<strong>`` gives bolder look and strong importance in search results.

### 38. Difference between ``<i>`` and ``<em>`` tag?
``<i>`` is a presentational element used to give italic look to the text.

Whereas ``<em>`` gives an italic look and importance in search results.

### 39. What do you mean by a Responsive Website?
The website is responsive when it looks good in all screen resolutions and device types.

To re-arrange the element's width and to display/hide any elements on the webpage, we can use CSS media queries.