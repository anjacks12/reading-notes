# Read 03: HTML Lists, Control Flow with JS and the CSS Box Model

Notes were made from Jon Duckett's HTML & CSS and JavaScript & jQuery books

## Chapter 3: HTML Lists

* Three types of lists: all three use `<li>` (list item), nested within the list
  * Ordered `<ol>`
  * Unordered `<ul>`
  * Definition `<dl>`
    * also includes definition term `<dt>` and definition description `<dd>`
* Nested lists: are lists within lists

## Chapter 13: CSS Boxes

* HTML tags/elements contain boxes around them; CSS can be used to style these "boxes" by using different properties and values
* Box dimensions: `width` and `height` changes dimensions
* Limiting width: `min-width` and `max-width` sets limits on width of box
* Limiting height: `min-height` and `max-height` sets limits on height of box
* Overflow content: `overflow: hidden` and `overflow: scroll` instructs the browser on what to do with content that is too large for the box
* Areas of the box: three areas around content that can be adjusted
  * Border: area between the margin and padding
    * `border-width`: controls width of border
    * `border-style`: controls style of border
    * `border-color`: controls color of border
    * can change each side of border differently:  
      2px (top) 1px (right) 2px (bottom) 1px (left)
  * Margin: area outside of the border
    * can change sides separately:  
      `margin-top`, `margin-right`, `margin-bottom`, `margin-left`
  * Padding: area between the border and content
    * can change sides separately:  
    `padding-top`, `padding-right`, `padding-bottom`, `padding-left`
* Centering content: `text-align: center`
* Changing Block elements to act like inline elements: `display: inline`
* Changing Inline elements to act like block elements: `display: block`
* Changing block elements to flow like inline elements but keep their block features: `inline-block`

## Chapter 2: Basic JS Instructions (pp. 70-73)

* Arrays:
  * Creates lists of values that are related to each other
  * Can contain different data types
  * Array literal: declares an array name like a variable and holds items inside square brackets, separated by a comma
    * the number assigned to each item is called an `index`
    * `.length` is a property that holds the number of items
    * can change the value of an item

## Chapter 4: Decisions and Loops (pp. 162-182)

* Switch Statements:
  * has a variable called the switch value; within the code block are cases with possible values for the variable; once the case that matches the value is found, that code is run
  * each case ends with a `break` that stops to code running once a match has been found
  * is faster than if/if...else statements because it stops once a match has been found
* Truthy Values: values are treated as if they were true
  * values that are: `true`, 1, `'things'` 10*2, `'0'`, `'false'`, true
* Falsy Values: values are treated as if they were false
  * values that are: `false` , 0 , `' '` , `NaN` or has no value assigned to the variable
* Checking Equality and Existence:
  * unary operator: can be used to check if an element exits
  * short circuit values: can also be used to check if an element exits
    * uses logical operators to read the expression from left to right and stops once a result is found
* Loops: three different types of loops (for, while, and do while)
  * loops only run if a condition is true
  * For loops: good if you need code to run for certain number of iterations
  * While loops: good if you don't know how many times the code needs to run; can set up a condition and have loop run as long as the condition is true
  * Do While loops: similar to while loops; difference is it runs the condition within the curly bracket at least once, even if the condition is false
  