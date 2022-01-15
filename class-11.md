# Reading 11: Audio, Video, Images

Resources: Notes were made from Jon Duckett's HTML & CSS book (see Resources)

## Chapter 16: Images (pp. 406-427)

* Controlling size of images in CSS
  * often sizes are images are usually consistent across web pages
  * having consistent sizing makes it easier to control the dimensions of the images easier and allows for a smoother loading of pages
  * common images sizes on webpages:
    * small portrait: 220 x 360
    * small landscape 330 x 210
    * feature photo 620 x 400
  * in CSS:
    * use the `width` and `height` properties and give them values to add dimensions to the images
    * if variable sizes are present, can also assign sizes like `small`, `medium`, and `large`
* Aligning images using CSS
  * `float` is commonly used to align images
  * can align multiple images by:
    * assigning them a class attribute with the size of the images (i.e. class="small") or can assign a class with the position of the image (i.e. class="align-right")
* Centering images using CSS
  * `<img>` act line inline elements, they can take on characteristics of block elements by `display: block` in CSS
  * two ways to center images when they display as block:
    * can use `text-align: center` on the containing element or can use `margin: auto` to cause the right and left margin to be equal and center the image
* Background images
  * can set a background image to a page in CSS by using:
  </br> `background-image: url("<file path of image>");`
  * background image can cover the entire page or portion of the page
  * usually the last thing to load on a page
* Repeating images:
  * `background-repeat` has 4 options
    * `repeat` shows vertically and horizontally
    * `repeat-x` shows horizontally only
    * `repeat-y` shows vertically only
    * `no-repeat` shows only once
  * `background-attachment` determines if the image should move with the user on the page or stay fixed to one spot
    * `fixed` stays in the same position
    * `scroll` moves up and down as user scrolls through page
* A background image can be positioned if it is not being repeated (`background-repeat: no-repeat`) by using `background-position`
  * `background-position` has 2 values:
    * horizontal: left, center, or right
    * vertical: top, center, bottom
  * can also use px or % for horizontal and vertical positioning
    * 0% = left or top
    * 50% = center
    * 100% = right or bottom
* Background shorthand:
  </br> `div {`
    </br>&nbsp;&nbsp;&nbsp;&nbsp;`background: 1.color 2.image 3.repeat 4.attachment 5.position};`
  </br> `div {`
    </br>&nbsp;&nbsp;&nbsp;&nbsp;`background: F0F8FF url("image/something.png") no-repeat center bottom};`
* Image rollovers and sprites
  * rollover is when a link/box changes style when the mouse hovers over it and/or changes styles again when the user clicks on it
  * sprites are when different parts of an image is used throughout the page
    * check out this blog post by [CSS Tricks](https://css-tricks.com/css-sprites/) to learn more about sprites
* Extra bits
  * CSS has use of gradients for additional design options for web development
    * check out [CSS Gradient](https://cssgradient.io/) for their gradient tool and to learn more
  * Using contrast for background images
    * when overlaying text on a background image, best to use low contrast so the text can be readable
    * if using a high contrast background image, can use a semi-transparent screen over the text to allow for better readability

## Chapter 19: Practical Information (pp. 476-492)

## Video and Audio APIs

Resource: [Mozilla: Video and Audio APIs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Video_and_audio_APIs)

* `<video>` and `<audio>` tags allows for video and their audio to be put into a web page
* because playback and audio controls on browsers can vary, it is advantageous to hide the default controls and create/style your own using HTML, CSS and JS; `HTMLMediaElement` is used to do this
* In the article above, a file was used that displayed a HTML5 video player with HTML and CSS included
  * Notable things about the HTML and CSS
    * HTML had four `button` tags for stop, play, rewind and fast-forward
      * these buttons has a `class` for the name (i.e. "stop", "fwd"), `data-icon` shows what icon should be on the button (i.e. "P", "R") and `aria-label` used to be read out by screen-readers (i.e. "play", "rewind") attribute
    * CSS has `visibility` to show or hide controls and `opacity` which allows for the controls to have a translucent appearance
  * Notable things about the JS
    * constants are created for all the functionality of the control (i.e. play, stop, rewind, fast-forward, timer)
    * `.removeAttribute();` is used to remove the default (native) controls and show the custom made ones from the HTML and CSS files
    * `.addEventListener();` are created to execute a function when an event is triggered on the control buttons

## Chapter 9: Flash, Video & Audio (pp. 201-206)

* Flash was a popular tool in the mid 90's and 2000's that made it easy to display animation on the web
  * not used much any more as other tools have been introduced that make creating animation easier and less tech devices support Flash
