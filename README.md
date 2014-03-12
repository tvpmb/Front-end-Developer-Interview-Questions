## General Questions:

* What version control systems have you used? 
* What is your preferred development environment? (OS, Editor, Browsers, Tools etc.) 
* Can you describe your workflow when you create a new feature? 
* Can you describe the difference between progressive enhancement and graceful degradation? 
* What does "minification" do? 
* If you have 8 different stylesheets for a given design, how would you integrate them into the site? 
* What tools do you use to test your code's performance? 
* If you could master one technology this year, what would it be? 
* Name 3 ways to decrease page load. (perceived or actual load time) 
* Explain the importance of standards.  

## HTML-Specific Questions:

* What's a `doctype` do, and how many can you name? 
* How do you serve a page with content in multiple languages? 
* What are `data-` attributes good for? 
* Describe the difference between cookies, sessionStorage and localStorage.  

## JS-Specific Questions

* Which JavaScript libraries have you used? 
* How is JavaScript different from Java? 
* What are `undefined` and `undeclared` variables? 
* What is a closure, and how/why would you use one? 
* What's a typical use case for anonymous functions? 
* Explain the "JavaScript module pattern" and when you'd use it. 
* how do you organize your code? (module pattern, classical inheritance?) 
* What's the difference between host objects and native objects? 
* Difference between: 
```javascript
function Person(){} var person = Person() var person = new Person()
```
* What's the difference between `.call` and `.apply`? 
* explain `Function.prototype.bind`? 
* When do you optimize your code? 
* Can you explain how inheritance works in JavaScript? 
* When would you use `document.write()`? 
* Explain AJAX in as much detail as possible 
* Explain how JSONP works (and how it's not really AJAX) 
* Have you ever used JavaScript templating, and if so, what/how? 
* Describe event bubbling. 
* What's the difference between an "attribute" and a "property"? 
* Why is extending built in JavaScript objects not a good idea? 
* Difference between document load event and document ready event? 
* What is the difference between `==` and `===`? 
* Explain how you would get a query string parameter from the browser window's URL. 
* Explain the same-origin policy with regards to JavaScript. 
* Explain event delegation. 
* Describe inheritance patterns in JavaScript. 

## JS-Code Examples:

```javascript
>~~3.14
```
Question: What value is returned from the above statement? 

```javascript
"i'm a lasagna hog".split("").reverse().join("");
```
Question: What value is returned from the above statement? 

```javascript
( window.foo || ( window.foo = "bar" ) );
```
Question: What is the value of window.foo? 


```javascript
var foo = "Hello"; (function() { var bar = " World"; alert(foo + bar); })(); alert(foo + bar);
```
Question: What is the outcome of the two alerts above? 


## jQuery-Specific Questions:

* Explain "chaining". 
* What does `.end()` do? 
* How, and why, would you namespace a bound event handler? 
* What is the effects (or fx) queue? 
* Optimize this selector: 
```javascript
$(".foo div#bar:eq(0)")
```

## CSS-Specific Questions:

* Describe what a "reset" CSS file does and how it's useful. 
* Describe Floats and how they work. 
* How do you serve your pages for feature-constrained browsers? 
* What are the different ways to visually hide content (and make it available only for screen readers)? 
* Have you ever used a grid system, and if so, what do you prefer? 
* Have you used or implement media queries or mobile specific layouts/CSS? 
* Any familiarity with styling SVG? 
* How do you optimize your webpages for print? 
* What are some of the "gotchas" for writing efficient CSS? 
* Do you use CSS preprocessors? 
	* If so, describe what you like and dislike about the CSS preprocessors you have used. 
* How would you implement a web design comp that uses non-standard fonts?
* Explain how a browser determines what elements match a CSS selector?  

## Optional fun Questions:

* What's the coolest thing you've ever coded, what are you most proud of? 
* Do you have any pet projects? What kind? 
