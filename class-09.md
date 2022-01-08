# Reading 09: Forms and JS Events

Resources: Notes were made from Jon Duckett's HTML & CSS book (see Resources)

## Chapter 7: Forms (pp. 144-175)

## Chapter 14: Lists, Tables & Forms (pp.330-357)

Resources: Notes were made from Jon Duckett's JavaScript & jQuery book (see Resources)

## Chapter 6: Events (pp. 243-292)

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