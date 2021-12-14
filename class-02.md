# Read 02: HTML Text, CSS Introduction, and Basic JavaScript Instructions

Notes were made from Jon Duckett's HTML & CSS and JavaScript & jQuery books (see Resources)

## Chapter 2: Text (pp. 40-61)

+ Structural markup are HTML tags that are used to edit the structure of  text, as in adding headings, creating paragraphs, bolding or italicizing words or adding subscripts or superscripts
  + `<h1>` through `<h6>`: headings go from 1 to 6 where `<h1>` being the largest and `<h6>` being the smallest
  + `<p>`: surrounds text and creates paragraphs
  + `<b>`: bold words
  + `<i>`: italicizes words
  + `<sup>` superscript
  + `<sub>` subscript
  + Whites space collapsing: browser does not show extra spaces
  + `<br  />`: creates a break, moves text to a new line
+ Semantic markup: provides additional information that relates to the content of the text for search engines or screen readers; not used to affect the structure of the text (that’s what structural markup tags are for):
  + `<strong>`: add importance; shows up bold in browsers
  + `<em>`: emphasizes words; italicizes them in browsers
  + `<blockquote>`: used for long quotes and shows indented in browser
  + `<abbr>`: used as an attribute to write out an abbreviation
  + `<cite>`: used when citing work:
  + `<ins>`: inserts text
  + `<del>`: deletes text
  + `<s>`: strikeout; puts a line through text

## Chapter 10: Introducing CSS (pp. 226-245)

+ Styling can be done through CSS in HTML structural markup tags
+ CSS rule contains a selector (the element) and declaration (what will be done to the element)
  + There are different types of selectors, some that can target elements with specific class or ids
  + The declaration contains a property and value
    + Property is the characteristic of the element that will be changed
      + Value is what the result of the change will be
        + Written as: <br />
          p {<br />
           color: blue;<br />
          }
+ External CSS is where the CSS file is attached by a link
  + Linking CSS file in HTML allows it to easily be linked to other pages without having to duplicate code
+ Internal CSS is where CSS is coded in the same HTML file inside the `<head>` using the `<style>` tag
  + This is not recommended as it would mean more coding than necessary
+ CSS works as a cascade; meaning it reads from top down where more recent, important or specified selectors can override the initial selector for an element
+ Child elements inherit the font-family of the parent element but not the background-color or border properties

## Chapter 2: Basic JavaScript Instructions (pp. 53-84)

+ Statements are step-by-step instructions of code for computers to follow
  + Can be organized into code blocks
+ Comments: are added in code to make notes or explanations to make reading the code easier; comments do not affect code in JavaScript
  + Single line comments use `//`
  + Multi-line comments use `*/` COMMENTS HERE `*/`
+ (Primitive) Data types: contain or make data (From class notes on 12/6/21)
  + Numbers: can include decimals and negative numbers
    + To revert a number that is a string (‘8’) back to a number, use ParseInt() (i.e. ParseInt(‘8’) to change back to 8)
    + String: letters, numbers or symbols enclosed in quotations
    + Boolean: True or False
    + Undefined: a primitive value assigned to a variable when no other value is assigned
    + Null: specifically defined as none, nothing or null; considered an object in JavaScript
+ Variable: can be thought of as a box that stores data (information) to be used to run the code
  + Declaring a variable: giving a name for a variable (i.e. var username)
  + Assigning a value: giving a variable a value (i.e. username = Sally; or height = 4)
    + Can be used to store numbers, string and a Boolean
    + Value of a variable can be changed to reflect the new value later in the code
+ Arrays: special variable that can store multiple data points with even different data types
  + This is helpful when the total number of data point is unknown, when working with a list or each item has an equal set of values
  + Arrays are placed within square brackets and separated by a comma
  + Each item in the array is assigned a number (index) that starts with 0
+ Expressions: evaluate a single value ( var username = Sally)
  + Or, it can take 2 values and return a single value ( var area = 5*4)
+ Operators: are used in expressions to create a single value from multiple values
  + Assignment operator `=`
  + Comparison operators `>` and `<`
  + Arithmetic operators are used to calculate values
    + `+` used for addition
    + `-` used for subtraction
    + `/` used in division
    + `*` used in multiplication
    + `++` used to add 1 to current number
    + `--` used to subtract 1 from current number
    + `%` Modulus; used to divide and return the remainder
  + String operators (+) is used in concatenation, or putting string together
    + When a string and number are concatenated, it will result in a string <br />"Hello"  + 10 will become Hello10

## Chapter 4: Decisions and Loops (pp. 145-162); only up to section on switch statements

+ Comparison operators evaluate conditions by comparing two operands (values) with each other to determine if it is true or false:
  + `===` strict equal to; values AND data types must be the same
  + `!==` strict not equal to; checks to see if both values AND data types are not the same
    + 5 = 5 (is true but using `!==` returns as false)
    + '5' = 5 (is false but using `!==` returns as true)
  + `>` greater than; `>=` greater than OR equal to
  + `<` less than; `<=` less than OR equal to
  + When comparing two values, usually structured as: (value1 >= value2)
  + When comparing two expressions, usually structured as:
    + ((value1 + value2) > (score1 + score2))
+ Logical operators: used when need to compare if more than one comparison operator and returns a value of true or false
  + `&&`: Logical And; both expressions must be true to return true
  + `||`: Logical Or; only one expression must be true to return true
  + `!`: reverses the return value; if expressions was true will return as false
+ If statements: checks a condition and if it is true, will run the code; if condition is false, code will not run
  + If (score >= 70) { <br />
      congratulate(); <br />
      }
+ If… Else statements: checks a condition and if it is true, will run code; if condition is false, will run another code
  + If (score >= 70) { <br />
      congratulate(); <br />
      } else { <br />
      encourage(); <br />
      }

## From “How to Write a Git Commit Message” by C. Beams (https://chris.beams.io/posts/git-commit/)

+ Well written Git commit messages help fellow developers see what changes have been made
+ A well cared for git log is important in maintaining a repo because it helps track and understand changes that were previously made
+ Three things a team should decide on when creating commit message convention:
  + Style, Content and Metadata

### Seven rules for a great Git commit message:

  1. Separate subject from body with a blank line
      + The text up to the blank line is treated as the commit title
  2. Limit the subject line to 50 characters
      + 50 characters is a rule of thumb; 72 characters is the hard limit otherwise; part of the subject line will be cut off
  3. Capitalize the subject line
  4. Do not end the subject line with a period
      + Because space is precious
  5. Use the imperative mood in the subject line
      + Write the Git commit subject line in a way that will describe what the update will do; “If applied, this commit will **your subject line here**” (if applied, this commit will release version 1.0.0)
  6. Wrap the body at 72 characters
        + Better to write body in a text editor where it can be set to wrap text at 72 characters since Git does not wrap text automatically
  7. Use the body to explain what and why vs. how
        + Explain why changes were made, how was it working before the changes were made, how it is working now and why you changed it the way you did
