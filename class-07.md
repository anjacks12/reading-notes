# Reading 07: Object-Oriented Programming, HTML Tables

Notes were made from Jon Duckett's HTML & CSS and JavaScript & jQuery books (see Resources)

## [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

* Domain modeling is creating a coding model to solve a problem; if it is well structured, it can demonstrate that the problem is well understood

## Chapter 6: Tables (pp. 126-145)

* Information can be displayed in a table or grid
* In HTML, tables are written in rows
* Table cell is each block in a grid/table
* Structure of a table:
  * `<table></table>` used to create table
  * `<tr></tr>` (table row) starts each row
  * `<td></td>` (table data) represents a table cell
* Table Heading:
  * `<th></th>` heading for a row or column; goes after `<tr>` and before `<td>`
    * empty cells help render page correctly by acting as a placeholder for empty `<tr>` or `<td>`
    * `scope` attribute is used to distinguish between columns or rows
      * `<th ="col">` for columns
      * `<th ="row">` for rows
  * Spanning Columns
    * `colspan` attribute used in `<tr>` or `<td>` tags if table needs to span across multiple columns (think <-- or -->)
    * `rowspan` attribute used in `<tr>` or `<td>` tags if table needs to span across multiple rows (think up or down)
  * Long tables made of three tags:
    * `<thead>` table heading
    * `<tbody>` table body
    * `<tfoot>` table foot

## Chapter 3: Functions, Methods, and Objects (pp. 106-144)

* `new Object ()` called a object constructor that creates blank objects
  * different from object literals in that each property and method ends with `;` instead of `,`; has the keyword `new` in front; object name in capitalized
  * creates may objects by using a function as a template to create same or similar objects
  * creating a new object is called creating an instance(s)
* Global scope/context
  * when a variable or function is ***not*** inside a function or object
  * the keyword `this` can differ in what property or object it refers to in these cases
* Arrays and objects can be stored in each other
* Built-In Objects
  * Browser Object Model
    * creates model of the current browser tab or window
      * child objects: document, history, location, navigator, screen
  * Document Object Model (DOM)
    * creates model of current web page; represents the whole page
      * child objects represented by items on the page (content held within element tags)
  * Global JavaScript Objects
    * does not form a single model; formed by a group of objects
      * objects that represent basic data types:
        * String, Number, and Boolean
      * objects that deal with real-world concepts:
        * Data, Math, and Regex