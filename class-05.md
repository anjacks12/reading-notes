# Read 05: Images, Color, and Text

Notes were made from Jon Duckett's HTML & CSS and JavaScript & jQuery books (see Resources)

## Chapter 5: Images
* use `<img>` for images
  * `scr`: tells browser where to find image (ie URL)
  * `alt`: description of image
  * `title`: additional information of image
  * `width` and `height`: sets dimensions of image
* `<figure>`: holds image and `<figcaptions>` (captions)
* 3 rules for creating images:
  1. save in right format
  2. save at right size
  3. measure images in pixels
* TL;DR (Too Long, Didn't Read [JPEG vs PNG vs GIF](https://blog.imagekit.io/jpeg-vs-png-vs-gif-which-image-format-to-use-and-when-c8913ae3e01d))
  * use JPEG for photos
  * use PNG for logos or things that contain text and objects with sharp contrasts
  * use GIF for animation

## Chapter 11: Color

* 4 ways to express color:
  * RBG values^^
  * Hex Codes
  * Color names
  * HSL (Hue, Saturation, Lightness) values^^  
  ^^Note: 'A/a' called alpha and represents opacity used in RBG and HSL

## Chapter 12: Text

* Can change font styles and size with different CSS properties like:
  * `font-family`, `font-size`, `font-weight`, `font-style`, `text-decoration`
* Can change spacing and alignment of text with:
  * `line-height`, `letter-spacing`, `word-spacing`, `text-align`, `vertical-align` `text-indent`
  * Can change the look of links through pseudo-classes in CSS:
    * `:link`, `:visited`, `hover`, `active`

## Notes from class

* `ESC`:wq is how to get out of vim (wq stands for write and quit)
* Organization of code:
  1. Global variables
  2. Function Declaration
  3. Executable code (function calls, alerts, prompts)
  4. Event listener (will discuss in later class)
* Forking repos in GitHub:
  1. fork the repo that you wish to work on
  2. copy URL of the forked repo
  3. git clone onto your computer and open repo
  4. A-C-P after changes
  5. back at your repo, click `contribute` and then `open pull request`
  6. click on `create pull request` and name the pull request and add comment about what was done
  7. click `create pull request`
* Merging Pull Requests in GitHub:
  1. review changes made from pull request, if looks good then approve it
  2. once approved, click `merge pull request`; should turn have a purple `merged` box on repo
  