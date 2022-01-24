# Reading 14a: CSS Transforms, Transitions, and Animations

## CSS Transforms

From "Learn to Code Advanced HTML & CSS": [Lesson 7](https://learn.shayhowe.com/advanced-html-css/css-transforms/)</br>

* `transform` property comes in 2 settings (2D and 3D)
  * 2D Transforms
    * `rotate` value in degrees where (+) degree rotates clockwise and (-) degree rotates counterclockwise
    * `scale` value changes the size with default value being 1
      * .01 to .99 makes the size smaller while 1.01 < makes the size larger; can scale on x and y axis using `scaleX` and `scaleY`
    * `translate` value shifts (or pushes or pulls) the element in different directions; can scale on x and y axis using `translateX` and `translateY`
    * `skew` value distorts element along x and y axis; can scale on x and y axis using `skewX` and `skewY`
    * can combine multiple transforms together in a single line without use of a comma
      * using `transform` multiple times will cancel out the previous one
    * `transform-origin` value will change the default position; can scale on x and y axis using `x y` positioning in either % or pixels
    * `perspective` value allows for vanishing point to appear that gives 2D images a 3D look; when set to `none` the perspective is turned off
  * 3D Transforms
    * changes elements on the z-axis
    * included in 2D transform values by using `rotateZ`, `scaleZ`, `translateZ`
      * `skew` cannot be transformed on z-axis

## CSS Transitions & Animations

From "Learn to Code Advanced HTML & CSS:: [Lesson 8](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)</br>

* text

From "Web Design Blog": [8 Simple CSS3 Transitions That Will Wow Your Users](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users/)</br>

* text