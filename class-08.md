# Reading 07: More CSS Layout

Resources:

## [Learn CSS Layout (from web.dev)](https://web.dev/learn/css/layout/)

Notes were made from Chapter 15 "Layout" of Jon Duckett's HTML & CSS book (see Resources)

[^1] [Flexbox vs. CSS Grid-Which is Better?](https://youtu.be/hs3piaN4b5I)

[^2] [CSS: Display-Block, Inline & Inline-Block](https://youtu.be/hgoFi0fCv3w)

* `display` property determines how contents within the box will act/flow in two ways:
  * normal flow is where layout/positioning of elements act either as `inline` or `block` elements within the box
  * `flex` or `grid` is used to create layouts for more than one element (child elements) within the box
* Flexbox:
  * a good mechanism for positioning items/creating layout on a single-axis (think x OR y axis)
  * aligns element's children next to each other (as in inline)
    * `align-items`, `justify-content`, and `flex-wrap` help modify positioning
  * can convert child elements to flex items by using `flex` property to make changes on individual items within a flex container
    * `flex-grow`, `flex-shrink`, and `flex-basis`
* Grid:
  * a good mechanism for positioning items /creating layout on multi-axis (think x AND y axis)
  * allows for more layout options for items than flexbox
    * grid allows for overlapping of content while flexbox does not [^1]
* Normal flow:
  * inline-block: allows `block` elements to have `inline` element properties and `inline` elements to have `block` element properties [^2]
  * floats: allows an image to move to the far right or left of the page while the text wrap around the image
  * multicolumn layout: allows elements to displayed as columns and allows
  * positioning:
    * relative:
    * absolute:
    * fixed:
    * sticky:
    * static:

