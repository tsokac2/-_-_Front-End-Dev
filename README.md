<h1 align="center">Front End Dev  - Concepts</h1>

### What is mobile-first design?
When a designer creates a website layout specifically for mobile and adapts it to bigger screens later on.

### What is WCAG?
Web Content Accessibility Guidelines are part of a series of web accessibility guidelines.<br/>
Best and the easiest way to make a website usable for all of your customers.

### Difference between reactive and adaptive designs?
Responsive designs utilize a layout and adjust the content to fit users' screens.<br/>
Adaptive design - different fixed layouts for different user screens.

### What are fall-back fonts?
Provide backup for the fonts - if one doesn't work properly the next is a backup.<br/>

### Optimize the webpage for prints.
Use high contrast between your background and text adjust font size to improve readability.

### How to lower specificity - *"change"* ID specificity over the class?
Normal ID syntax  - ```#myId {color: red};```<br/>
Override ID syntax -  ```[id="myId"]{color: red;}```<br/>
```<p class="myClass" id="myId"></p>```

### How do you plan accessibility?
- Keyboard navigation
- Text ```alt="image content"``` HTML attribute for images
- Colour Contrast
- Element Sizes and font sizes + spacing and padding

### Example of the no-semantic elements?
`<span>` - inline element - no-semantic<br/>
`<div>` - box element  - no-semantic

### How to manage z-index in an App?
Use Saas variables:<br/>
```
$zModal: 100;
header { z-index: $zModal; }
```
### Cross-browser testing?
- BrowserStack
- Virtualization
- Docker

### Hov remove the margin in the inline-block element when kept under a div?
Assign the font size of a parent if the inline-block element to **0px** - apply font size to the inline element.