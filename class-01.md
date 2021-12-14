# Read 01: Introductory HTML and JavaScript

## Chapter 1: HTML
+ HTML consists of elements (or tags) that tells/instructs a browser on how materials should be displayed on a web page
+ Elements contain opening tags `<p>` and closing tags `</p>` that are sandwiched between content

    i.e. `<p>`CONTENT IN BETWEEN`</p>`
+ Empty elements do not have closing tags
+ Elements can also contain attributes that describe the characteristic of an attribute and contains a name and a value
    + Name: the name of the attribute (i.e. "href" for links or "src" for images)
    + Value: the specific information (i.e. the URL address for the link or file pathway for an image)

    i.e. `<p` attribute_name=attribute_value`>`CONTENT IN BETWEEN`</p>`
+ Some other key HTML structure elements include:
    + `<body>`, `<title>`, and `<head>`

### Chapter 8: Extra Markup
+ DOCTYPE: informs the browser which version of HTML is being used
+ Comments can be included in the HTML without showing up on the web page by using:
        `!<--`COMMENTS`-->`

    + This can also be used to stop code from executing and remain unseen
+ Common Attributes:
    + id: also known as "global attribute" because it can be used in any element
        + used to identify a specific element to be styled (by CSS) differently than the others
    + class: can also be used in any HTML element
        + used to identify multiple elements for special (CSS) styling
+ Block Elements: `<h1>`, `<p>`, `<ul>`, `<il>`
    + each of these elements form a new line
+ Inline Elements: `<a>`, `<b>`, `<em>`, `<img>`
    + each of these element remain inline (on the same line)
+ `<iframe>`: inserts a section from another web page into the working web page
    + scr, height and width attributes are needed
+ `<meta>`: contains information about the web page but is not shown on the web page
    + `<head>` element is contained here
+ Escape characters: are ways to use characters that have a special designation as regular characters

### Chapter 17: HTML5 Layout
+ `<header>` and `<footer>`: appears at the top and bottom of the web page
    + they can also be used to contain multiple sections in a web page (i.e. blog post)
+ `<nav>` or navigation: used to hold links to navigate through a web page
    + has also been used at the bottom of web pages to display links for additional information about a page or company
+ `<article>`: acts like a container for multiple sections in a web page like articles or blog posts
+ `<aside>`: can be used in 2 ways:
    + inside an `<article>` it can hold unimportant information that was referenced in the article like quotes or images
    + on its own, it can act like an `<article>` and contain things related to the whole web page like reference links or relevant sites
+ Older browsers may not recognize HTML5 elements, without the additional help, browsers will treat all elements as inline elements
    + Simple CSS code to tell it which elements are considered block elements will help
    + Older versions of Internet Explorer may also need JavaScrip code added as well (like HTML5 shiv or HTML5 shim)

### Chapter 18: Process and Design
+ Need to evaluate who the target audience is/will be before designing a web page
+ Need to determine why they will be visiting the web page and what do they expect to get out of visiting
+ The frequency on visits should be considered as well since frequently visited sites may need more maintenance and updating
+ Site maps: are a good way to get an outline of what content and pages the website will have
+ Wireframes: are a sketch or diagram of what the layout will look like
    + does not contain any pictures or images, just place holders to get an idea of the content layout
+ Visual Hierarchy: the order of information of the website
    + Includes factors like size, color and style of font
    + strategic placement of images
+ Grouping and Similarity: grouping related content together through design

### Chapter 1: The ABC of Programming
+ What is script and how do I create one?
>"A script is a series of instructions" [^1]
+ Steps in writing code:
    1. Define the goal: why is this task being done?
    2. Design the script: what are the step-by-step tasks to get the final result?
    3. Code each step: creating a flow chart is most handy!
+ What is needed in creating a code?
    + Vocabulary: understanding the language (terms)
    + Syntax: knowing how to put the language together to form code
    + Programmatic approach: understanding how to "think" like a computer and determine how a code should be written so that i can be correctly executed
    >"Computers solve problems **programmatically**; they follow series of instructions, one after another. The type of instructions they need are often different from the type of instructions you might give another human."[^2]
+ How do computers fit in with the world around them?
    + Programmers use data to create models of the world
    + Physical things are represented as **objects** and the characteristics associated with the objects are called **properties**
        + Each property contains a **name** (description of the property) and **value**
    + **Events** are occurrences initiated by user interactions
    + **Methods** are the things done to the objects that can change the value of the object's property
+ How HTML, CSS, and JavaScript fit together:
    + HTML is the content layer where the web page gets its structure
    + CSS is the styling layer where the HTML is enhanced by adding color, background, and layout changes
    + JavaScript is the dynamic layer where it provides interaction between the user and webpage
+ Creating a basic JavaScript:
    + JavaScript is a text file like HTML and CSS that can be saved as its own file using .js as its extension
    + JavaScript can be linked to the HTML page by using the HTML element `<script>`
    
        + i.e. `<script src="`JAVASCRIPT_FILE`.js"></script>`


[^1]: Duckett, J. &nbsp;(2014). &nbsp;*JavaScript & jQuery Interactive Front-End Web Development*.&nbsp; John Wiley & Sons, Inc.&nbsp; pg 14.

[^2]: Duckett, J.&nbsp; (2014).&nbsp; *JavaScript & jQuery Interactive Front-End Web Development*.&nbsp; John Wiley & Sons, Inc.&nbsp; pg 21.


Reading Notes were made from:
Notes were made from Jon Duckett's HTML & CSS and JavaScript & jQuery books (see Resources)