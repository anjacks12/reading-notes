# HTML Links, JS Functions, and Intro to CSS Layout

Notes were made from Jon Duckett's HTML & CSS and JavaScript & jQuery books (see [Resources](#table-resource)]

### Chapter 4: Links
* links use the `<a>` element and `href` attribute
* used to link other websites to your webpage by using absolute URLs
  * absolute URLs are full web address for a page
* can also be used to link within the same webpage by using relative URLs
  * relative URLs are shorthand file names
    * only can be done if files are in the same folder
  * can link within the same web page if files are saved in different folders with relative URLs by adding the path of the folder (see pg. 82 for example)

### Chapter 15: Layout

* CSS treats each HTML element like it has a box around it
  * elements can either be block-level or inline
* Containing elements are the outer block-level elements that contain another block-level element within
  * like a `<header>` that holds `<nav>` or `<body>` that holds `<p>`
* CSS can position elements through positioning schemes:
  * normal flow: normal, default layout
  * relative position: shifts the position of an element from its normal spot to another while not affecting the position of the elements around it
  * absolute position: shifts the position of an element and the other remaining elements rearrange themselves as if the shifted element was no longer there
* CSS can also position boxes through box offset
  * fixed positioning: changes the position of an element and keeps it fixed there, even while the user scrolls down the page
  * floating positioning: moving an element to the far right or left and having the other elements shift around the moved element

### Chapter 3: Functions, Methods and Objects

* Function is a group of statements that tell the computer to do a task
* Declaring a function: by giving it a name, parentheses and curly brackets that hold the statements (and a semicolon of course)
* Calling a function: this is like telling a function to run; done by calling the function's name with parentheses and semicolon included
* some functions contain parameters (that's what goes in those parentheses), these are the pieces of information the function needs to run
  * to run a function with parameters, it needs arguments when called; arguments are the data to run the functions, this is what's inside the parentheses when calling a function

### [6 Reasons for Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

* Pair programming is where two work together on a project while one controls the actual coding and the other "navigates"
* This method has been found to be an efficient way to learn coding by practicing speaking, reading, writing and listening to code
  * It is also an efficient way to reduce the chances of error and produce higher quality of code
* Used in interviews as a way for employers to access the interpersonal interaction of the interviewee 
* Allows students or new developers to learn from each other
* Working in pairs help make work more productive
* If a problem arises, can collaborate with each other to find ways to solve the problem