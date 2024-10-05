<center> <h1 style=color:red;>Introduction to HTML, CSS, & JavaScript </h1> </center>


<center> <h2> Module 1:  HTML Overview </h2> </center>

* ***What is HTML?***

**Hypertext Markup Language (HTML):**
    * language of the Internet
    * Designed originally for sharing scientific documents
    * Adapted to suit the requirement for displaying various types of documents as web pages


**Objectives of HTML5:**
    * Defines a single language which can be written in HTML or XML syntax
    * Interoperability with earlier HTML implementations Improves markup for documents
    * Includes markup and APIs for idioms, such as web applications



* **HTML Features***

**HTML5 features:**
    * Categorizes web pages into different sections
    * Includes tools for data management, drawing, video, and audio
    * Facilitates the development of cross-browser applications for the web and portable devices
    * ALlows flexibility to develop exciting and interactive websites.
    * Helps create engaging user experience by providing an experience similar to desktop applications.
    * Allows for enhanced multiple-platform development.

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset= 'utf-8'>
        <title>Simple Interest Calculator</title>
    </head>
    <body>
        <p>Example paragraph</p>
        <!-- this is a comment -->
    </body>
</html>
```

* `<!DOCTYPE html>`: Declaration tag that represents the document type.

* `<head>` element can contain the following tags:
    * title (`<title>`)
    * scripts (`<script>`)
    * style (`<style>`)
    * style sheet links (`<link>`)
    * meta information (`<meta>`)
    * browser support information and other initialization functions (`<base>`)

* ***HTML Management and Support***

* HTML5 themes provide:
    * Syntax that are compatible with HTML4 and XHTMLI
    * New and refined APIs for video and audio elements, offline web apps, and drag and drop
* HTML5 web Apps have:
    * Improved search indexing with meta tags
    * Better page load times
    * Enhanced user experience
    * HTML5 elements enable you to define web page structure and content


* ***HTML Scripting***

* **Scripting**
* Used within the `<script>` tag or within a separate file, which is called in the HTML code
* Provides an interactive user experience
* Used for various tasks, such as:
    * Form validation
    * Dynamic content changes
    * Image manipulation
* Can be disabled in browser contexts

* **Enabling scripting**
Scripting is enabled in a browser context when the following conditions apply:
    * The browser supports scripting
    * The user has scripting enabled
    * The browser context does not have the sandboxed browsing content flag set
        * `<meta http-equiv="Content-Type" content="text/html-sandboxed; .....`
        * `<iframe sandbox "http://maps.google.com/?ll=" + theLat + "," + theLong + "&z=16&output=embed\ "></iframe>`

* **HTML document API - DOM tree accessors**
    * Every HTML and XML document is represented by a document object
    * The DOM tree accessors are HTML document APIs that provide access to all the HTML elements on a page
    * The property to access the HTML elements is prefixed by the word document

<center> <h3 style=color:orange;> Summary & Highlights </h3> </center>

In this module, you learned that:

* HTML provides the basic structure and content for a website using tags. 
* Tags represent the elements of an HTML page. 
* The HTML DOM Tree describes how a website is structured. 
* HTML uses APIs to enhance the user experience, providing features for advanced animation, audio, and video. 
* Scripting provides a more interactive user experience when browsing websites. 
* It is recommended to not rely on scripting as it can be disabled. 
* HTML5 sandboxes help manage iframe mashups.  
* HTML5 Browser Support Tables describe which browsers support which HTML5 features. 
* JavaScript is used to check if an element is supported by a browser. 
* CSS provides consistent style and design throughout the website. 
* There are two types of CSS layouts to design websites: fluid and fixed. 

<center> <h2> Module 2:  HTML5 and CSS </h2> </center>

|**TAG** | **DESCRIPTION** |
| ------ | --------------- |
| `<article>` | Content from an external source - news article, blog, or forum |
| `<aside>` | Content aside from the page content |
| `<audi0>` | Used to embed sound content |
| `<canvas>` | Used to draw graphics |
| `<datalist>` | Provides a list of predefined options for input controls |
| `<details>` | Used to show or hide contents |
| `<embed>` | Embeds an external application or interactive content into page |
| `<figcaption>` | Caption for the figure tag |
| `<figure>` | Specifies self-contained content |
| `<footer>` | The footer of a document or section |
| `<header>` | Specifies a group of introductory or navigational elements |
| `<keygen>` | Specifies a key-pair generator field used in forms |
| `<mark>` | Represents highlighted text |
| `<meter>` | Used for measurements with minimum and maximum values |
| `<nav>` | Specifies navigation for a document |
| `<output>` | Represents the result of a calculation |
| `<progress>` | Specifies the state of work in progress |
| `<section>` | Defines sections in a document or article |
| `<source>` | Used to specify multiple media resources for media elements |
| `<summary>` | Defines a visible heading for the details tag |
| `<time>` | Used to specify the date or time in a document |
| `<video>` | Specifies video, such as a movie clip or video stream |
| `<!-- -->` | Comments in source that are not displayed in the browser |

* **HTML5 structural elements**
* The `<div>` tag provides flexible control for applying a style to parts of a document
* HTML5-specific structural elements can be used inside the `<div>` tag
* The element describes the function or the type of data that is contained within
    * A `<p>` element is a paragraph that contains text
* The `<div>` tag has no innate semantic meaning besides the logical grouping of the content
* `<article>`
    * Represents a block of code that can logically stand alone
    * Examples include a newspaper article, user comments, blog entries
    * Used with the `<time pubdate ...>` attribute to provide a publication date for the article
* `<section>`
    * Represents a logical separation in a document, for example, chapters of a book
    * Accompanied with a heading
* `<header>`
    * Defines the header information for a page
    * Used for section table of contents or to wrap navigational links or logos
* `<footer>`
    * Defines the text at the bottom of the page
    * Used for copyright information

* **Elements for grouping contents**
* `<aside>`
    * Provides additional information that is related to the main discussion
    * Extracts and displays further content or navigates to additional resources without detracting from the main discussion
    * Used for cautions, notes, or to wrap navigational links
* `<figure>`
    * A self-contained element referred to from the main content
    * Embeds graphics, photographs, or code segments
    * Can be moved to an appendix without affecting the flow of the document
* `<figurecaption>`
    * Defines the caption for the contents of the `<figure>` element

* **Input for color chooser: `<input type="color"/>`**
    * Allows a user to select color
    * Dialog varies depending on browser
    * Not all browsers support such input type
    * Some browsers display the input type as regular text

* **Input for date: `<input type= "date"/>`
    * A date control (year, month, day) with no time zone
    * Input dialog varies depending on the browser

* **Input for date and time: `<input type="datetime-local"/>`**
    * Provides input for a date and time (year, month, day, hour, minute, AM/PM) with no time zone.

* **Input for emails: `<input type="email"/>`**
    * Displays a regular text input field
    * Accepts only a valid email format

* **Input of type number: `<input type:"number", min= "1", nax= "10" />`**
    * Takes a numeric value as input
    * Can be used with minimum and maximum values

* **Input of type range: `<input type="range" min="5" max=" 10" />`**
    * Takes a numeric range as input

* **Input of type search: `<input type="search"/>`**
    * Similar to the text field but differs in style
    * WebKit-based browsers return a history of recently searched text strings
    * The search input field on the Safari browser has rounded corners


* **Input of phone numbers: `<input type="tel">`**
* Used for telephone numbers
* Provides a text entry field in the
* Does not enforce numeric only input
    * Accepts characters, such as the plus sign and hyphens

* **Input for URLs: `<input type="URL">`**
* Used to validate if the input is a properly formatted URL or web address

* **Input attribute "list"**
    * Used with `<datalist> `tag that include the options list
    * Useful for auto-complete functionality

* **Input attribute "placeholder"**
    * Provides an example of the input text format in a lighter shade of text
    * `< input type="email" placeholder="example@email.com">`
    * Does not send the placeholder text as input during for submission.

* **Input attribute "required"**
    * Indicates that the field is required
    * `<input type="email" required>`


* **Validation fallback**
    * What if browser-based validation is not supported?
        * Use prebuilt script libraries, such as JavaScript and JQuery libraries
        * Assume browsers will support more HTML5 features over time
        * Leave all final validation to server-side
        * Include custom client-side validation that is attached to the form submit event handler

* ***CSS***

* **Media Independent with HTML5, Javascript, and CSS**
    * Gives developers flexibility to target web and mobile devices
    * Provides features that interactive applications without requiring plug-in technologies
    * Provides assistive technologies for vision impaired people

* **What is CSS?**
    * Design that is layered over the top of an HTML Web page
    * Describes how HTML elements are displayed
    * Creates a uniform look throughout each elernent Of each page Of the website
    * Child and descendant elements often inherit styles that are defined for parent elements


* **CSS design and coding**
    * Important concept to separate data from design:
    * Data is sent to the browser using HTML, and design is applied to that data using a CSS
    * Allows rendering of Web pages without design using special accessibility needs
    * Allows machines to index a Website without design
* CSS can be coded as a style attribute in an HTML tag, a head section of a document, or an external document

* **What elements can CSS control?**
CSS controls a document's appearance and specifies style rules for the following web page elements:
* Fonts
* Text
* Colors
* Backgrounds
* Sizes
* Borders
* Spacing
* Positioning
* Visual effects
* Tables
* Lists

* **Guidelines for base styles**
    * Colors use Red-Green-Blue (RGB) hexadecimal light values
    * Size use pixels, ern, or a percentage
    * Text can be aligned left, right, or center
    * Floats can also be left or right
    * Vertical alignments must be top, middle, or bottom
    * Fonts can be any specific font or font family, such as serif, sans-serif, or monospace or even a downloadable font

* **Choosing a Layout**
* In a fixed layout:
    * You specify the height and width of elements
    * Values remain the same regardless Of screen size
    * You specify elements using pixels
* The type of layout should depend on the type and amount of content and the target audience.

* **Applying CSS to HTML**
* 1. Inline CSS:
    * Used for single HTML element
    * HTML documents get messy quickly
    * Insert the style attribute inside any HTML element
* `<p style= "color:red;">A red paragraph.</p>`

* 2. Internal CSS:
    * Used for a single page
    * Increases load
    * Add a `<style> `tag to your HTML document
* `<style> body {background-color: yellow;} </style>`

* 3. External CSS:
    * Used to style an entire website
    * Can be linked to from other pages
    * Add a `<link>` tag to the` <head>` tag
* `<head> <link rel= "stylesheet" type="text/css" href= "style.css"> </head>`

4. 
* Can use a combination of all three methods
* The type with the highest priority is applied

```plaintect
Highest  | Inline > Internal > External | Lowest
Priority |                              | Priority
```

* ***CSS Frameworks***
* CSS frameworks assist in implementing UI elements and creating dynamic web pages
* Plain (Vanilla) CSS lets developers write the styles and layouts of a website
* Utility-first frameworks provide utility classes to help build one's own styles and layouts
    * For example: Tailwind CSS
* Component frameworks provide pre-styled components and templates that can be implemented onto a website
    * For example: Bootstrap

<center> <h3 style=color:orange;> Summary & Highlights </h3> </center>

In this module, you learned that:

* CSS creates a uniform look throughout each element of each page of the website. 
* CSS is usually coded in external style sheets and creates base styles for a website. 
* CSS frameworks assists in implementing UI elements and creating dynamic web pages. 
* CSS has two types of frameworks: 
* Utility-first frameworks, which provide utility classes to help in building one's own styles and layouts. 
* Component frameworks, which provide a wide selection of pre-styled components and templates that can be implemented onto a website. 
* Plain (Vanilla) CSS lets developers write the styles and layouts of a website. 
* HTML5 elements provide structure and function to websites. 
* HTML5 uses the <input> tag to allow users to input information.

<center> <h2> Module 3:  JavaScript </h2> </center>

* **The Nature of JavaScript**
* Derived from the ECMAScript standard
* Originally designed to run on Netscape Navigator
* Not related to Java
    * Interpreted and complied
* JavaScript interpreters embedded in web browsers
    * Add dynamic behavior to otherwise static web content
* Core feature of Asynchronous JavaScript and XML (Ajax)
    * Works with HTML, CSS, XML, and JSON.


* **JavaScript Primitives**
* Primitives are values and have no properties or methods:
* number
* string
* boolean
    * True or false
* null
    * Represented by null
* undefined
    * A data type has not been assigned, or the variable does not exist.

* **Wrapper Objects**
* Some of the primitive data types have corresponding wrapper objects
* Allows an object of the related type to be created
* Stores a primitive value and offers methods with which to process it
* Wrapper objects have the same name as the primitive type, but they begin with a capital letter

* **Array Objects**
* Contain methods and properties used to store data
    * Accessible by indexed keys
    * Use a zero-based indexing scheme
    * Grow or shrink dynamically by adding or removing elements
    * Length property is the largest integer index in the array

* **Declaring Array Objects**
* Declaration of an array can use either an array literal or an array constructor
* Array constructors use the new array keyword and specify the array elements as parameters
```javascript
numArray = new array(0, 1, 2, 3, 4, 5);
numArray.length // returns 6
```
* Array literals create an array and initialize the elements in the array
```javascript
colors = ["red", "yellow", "green"]
```

* **Date Objects**
* The Date object is a snapshot of an exact millisecond in time
    * Represented in the format YYYY-MM-DD 00:00:00 UT
* There are number of ways to provide parameters to the Date constructor
    * Example without a parameter:
    ```javascript
    var today = new Date(); // returns the local date and time
    ```
* JavaScript automatically applies the toString() method if you attempt to display the
date on a page or alert box

* **Error Objects**
* Error object instances are created when an exception is thrown
    * Properties of the error object instance contain information about the error
    * message: A description of the message
    * name: Identifies the type of error, such as TypeError, RangeError, or URIError

* **Custom Error Types**
* Error object instances can be created by invoking one of the constructors for creating an error object
    * Custom error objects can be created
    * For example:
        ```javascript
        throw new Error( "Only values 1- 10 are permitted")
        ```

* ***A primer on variables***
* Variables are:
    * Containers for storing data values
    * Used and modified throughout a program's execution
    * Declared with the var keyword followed by variable name
        ```javascript
        var age;
        54;
        var age
        ```

    * Values can be assigned and reassigned
    * Data type does not need to be declared
    * Data type is assumed during assignment
    * Variable type can change during program execution

    * var keyword:
    * If not assigned a value, it is undefined
    * JavaScript reads var as a numeric or string variable based on the value assigned
    * JavaScript does not assign a zero or an empty string value
* Rules for variable names, or identifiers:
    * Name must start with a letter, underscore (_), or a dollar sign ($)
    * Subsequent characters can also be digits [0-9]
    * Identifiers are case-sensitive
* Variable scope declared:
    * Within a function have local scope
    * Outside of a function have global scope
    * Without the var keyword have global scope and have a value of undefined.

* Program execution is controlled by control statements:
    * Conditional statements like if...then...else
    * Switch statements
    * Repeat statements like for loops and while loops

* ***Functions***
A block of code that can be called from any point in a script after being declared
* Parts of a function:
    * Keyword function
    * Name of the function
    * Parenthesis with optional parameters
    * Curly braces with the associated logic
    * Return statement (optional)

* Functions example
```javascript
function add(n, m) {
    return n + m;
}
add (1, 2); // returns 3
add(1.23, 3.45); // returns 4.68
add ("hello", "world"); // returns "helloworld"
```

* Data types are determined by the values of the arguments that are being passed to the function.
* If no specific return type is declared, then the function returns whatever type is required.


* ***Prototypes***
* Defines properties and methods for all instances of the object
* Exists for all JavaScript objects that can be constructed with the new keyword
```javascript
function Car (make, model, year) {
this.make= make;
this.model= model ;
this.year= year ;
}
```

* Objects inherit all properties and methods from their prototype
* Prototype properties and methods can be changed in one call

* ***Self-executing functions**
* Self-executing or auto-invocation functions:
    * Start running immediately after they have been declared
    * Functions and variables are isolated from the rest of the script
    * Can be an anonymous (unnamed) function
```javascript
(function () {
// statements
})();
```
* Used to initialize data or to declare DOM elements on the page

* ***JavaScript API***
* How to retrieve a reference node using document.getElementById and document.getElementsByTagName
* How to create an element using document.createElement and place it using insertBefore, appendChild, or replaceChild
* How to modify elements using element.innerHTML, element.style and element.setAttribute
* How to manage a window object using functions that include window.open and window.dump("message")



<center> <h3 style=color:orange;> Summary & Highlights </h3> </center>

In this module, you learned that:

* JavaScript is a scripting language that enables developers to add dynamic content to web pages.
* JavaScript variables are declared using the 'let' or 'const' keywords and take their type from the value assigned.
* Program execution is controlled by statements like If…Then…Else, Switch, For loops, and While loops.
* JavaScript uses blocks of code, called functions, that can be called from anywhere in the script.
* New methods and properties can be added to an object by modifying the prototype for that object.
* Prototypes allow you to define properties and methods for all instances of a specific object.
* Client-side scripts are programs that accompany HTML documents and are used by developers to incorporate more interactive elements.
* The script tag can incorporate a script within an HTML document or call a script from an external file.
* The Document Object Model (DOM) is the programming interface between HTML or XHTML and JavaScript.
* Developers can access HTML DOM elements from JavaScript scripts using the correct DOM notation.
* APIs are often used to access HTML DOM elements in web pages.