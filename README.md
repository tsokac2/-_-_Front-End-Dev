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


### How to lower specificity - *"change"* ID specificity over the class?
Normal ID syntax  - ```#myId {color: red};```<br/>
Override ID syntax -  ```[id="myId"]{color: red;}```<br/>
```<p class="myClass" id="myId"></p>```

## CSS

### Difference between inline and inline-block elements?
```display: inline-block;``` allows to set a *width* and *height* on the element.<br/>
```display: inline;``` - can't define *width* and *height* on the element.


### Hov remove the margin in the inline-block element when kept under a div?
Assign the font size of a parent if the inline-block element to **0px** - apply font size to the inline element.


### Difference between container and container-fluid?
*Container* - provides a responsive fixed-width container<br/>
*Container-fluid* - provides a full-width container, spanning the entire width of the viewport.


### When to use !important?
Avoid using it as much as possible.
Use specificity to avoid it.
Don't use it.


### Break points in Bootstrap?
| Breakpoint |		Class infix |	Dimensions |
| ---------- | ---------------- | -------------|
| x-small		 |	xs 				| < 576px   |
| small		     |	sm  			| >= 576px |
| medium			 | md  			| >= 768px |
| large			 | lg  				| >= 992px |
| Extra large		 | xl 			| >= 1200px|
| Extra extra 	 | xxl				| >= 1400px|


### 1 REM = ? PX
REM - (root-em) - unit dictate elements' font-size relative to the size of the root element
**Font-size = 16px => 1 REM = 16 px** - in most cases


### CSS animation properties?
- animation-delay
- animation-direction
- animation-duration
- animation-fill-mode
- animation-iteration-count
- animation-name
- animation-play-state
- animation-timing-function

### CSS Preprocessors?
Sass
Less
Stylus
PostCSS

### What advantages of using SCSS over CSS?
Helps you write CSS codes easily by letting you use loops, functions, import, variables, and math operations, thus making CSS writing more powerful.


### CSS Resource(s)?
- StackOverflow
- Mozilla MDM DevDocs
- YouTube

### Cross-browser testing?
- BrowserStack
- Virtualization
- Docker

### Flexbox properties?
- flex-direction
- flex-wrap
- flex-flow
- justify-content
- align-items
- align-content


### How to manage z-index in an App?
Use Saas variables:<br/>
```
$zModal: 100;
header { z-index: $zModal; }
```