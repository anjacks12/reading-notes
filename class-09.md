# Reading 09: Forms and JS Events

Resources: Notes were made from Jon Duckett's HTML & CSS book (see Resources)

## Chapter 7: Forms (pp. 144-175)

* Forms is a way to collect information from the user
  * Think: user name, email address or keywords in search engines
* Forms are created in HTML using different types of form controls to create/structure what the form will look like and what type of information will be collected from the user
  * Forms are styled using CSS
* HTML element tags used to create forms also are paired with one or more attributes and value(s):
  * `<form>` where form controls are held in
    * attribute = value pairs: `action = URL`, `method = get/post`, and `id = name of id`
  * `<input>`: 
    * can be for text or password; the value of the `type`attribute determines what input is collected
      * attribute = value pairs: `type = "text"` for text and `type = "password"` for passwords
    * can also be used to create radio buttons or checkboxes; the value of the `type` attribute determines which is created
      * `type = "radio"` creates radio buttons and `type = "checkbox"` creates checkboxes
    * can also be used to create a box to upload a file or submit button
      * `type = "file"` creates a box that allows files to be uploaded
      * `type = "submit"` creates a submit button
      * `type = "image"` can be used to create an image for the submit button
  * `<textarea>`: used to create a space where texts with multiple lines can be collected (think comment or question box)
    * name, number of columns and rows are the attribute/values usually associated with this element
  * `<select>` used to create a drop down list or multiple selection box
* Labelling form controls is done by using `<label>` and the attribute `for` which is has a value of the form control it belongs to
  * i.e. for a control form that collects a username: `<label for="username">` Username `</label>`
* Grouping form elements can be done using `<fieldset>` and `<legend>`

## Chapter 14: Lists, Tables & Forms (pp.330-357)

* CSS is used to style forms and tables; doing so allows for more continuity in how forms and tables display in different browsers
* Lists can be styled by using the `list-style-type` property
  * different types of bullets can be used for unordered lists
    * `none`, `disc`, `circle`, or `square`
    * images can also be used in bullets if a URL is available
      * i.e. `list-style-type: url("img/smiles.png");`
  * different types of numbering can be used for ordered lists
    * `decimal` (1 2 3), `decimal-leading-zero` (01 02 03), `lower-alpha` (a b c), `upper-alpha` (A B C), `lower-roman` (i. ii. iii.), `upper-roman` (I II III)
  * position of markers can be changed from either being outside the block of text or inside the block of text:
    * `list-style-position: outside;` or `inside;`
  * List short hand: `list-style:` can put marker style, image and position in any order
* Table cell borders:
  * empty cells can have their borders shown or hidden
    * `empty-cells: show` or `hide`
  * spacing between borders can be adjusted or collapsed (no spacing)
    * `border-spacing: separate` with spacing determined via number of pixels or `border-spacing: collapse` for no spacing between borders
* Styling and alignment can be done using CSS on the different types of control forms as well as for fieldsets and legends

Resources: Notes were made from Jon Duckett's JavaScript & jQuery book (see Resources)

## Chapter 6: Events (pp. 243-292)
