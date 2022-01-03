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
* Positioning: different schemes allows for different controls of layout
  * Inline-block: allows `block` elements to have `inline` element properties and `inline` elements to have `block` element properties [^2]
  * Floats: allows an image to move to the far right or left of the page while the text wrap around the image
  * Multicolumn layout: allows elements to displayed as columns and allows
  * Normal: see above
  * Relative: shifts the position of an element from its normal spot to another while not affecting the position of the elements around it
  * Absolute: shifts the position of an element and the other remaining elements rearrange themselves as if the shifted element was no longer there
  * Fixed: changes the position of an element and keeps it fixed there, even while the user scrolls down the page
* Different devices have different screen sizes and resolutions; a factor that should be considered when designing a page
  * resolution is the number of pixels on a screen (length x height)
  * higher the resolution, the smaller the text looks
  * designers aim to create pages within 960 - 1000 pixels wide due to different screen sizes
  * having key content within 570 - 600 pixels height is a common practice by designers to let the user see that the page has relevant information for the user
* Fixed width layouts:
  * content of layout does not change if the window is increased or decreased in size
    * measured in pixels
* Liquid layouts:
  * content of layout stretches and contracts when size of the window changes
  