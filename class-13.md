# Reading 13: Local Storage

## From "Dive into HTML5" by Mark Pilgrim

[“No. 7 The Past, Present, and Future of Local Storage for Web Applications”](http://diveinto.html5doctor.com/storage.html)

### "HTML5 Storage" is a spec in most browsers known as web storage

* this allows for websites to store named key-value pairs after the user has left the site
* accessed by using `localStorage` object
  * the data is stored as a string but the value pair can be stored as a string, boolean, number, or float (basically any data type in JS) but the value gets stored as a string so JS functions are needed to revert the string back to a number
* wether the browser supports this specification can be tested by using a function
  * the reading suggests the one from [Modernizr](http://diveinto.html5doctor.com/detect.html#modernizr)
* objects can be treated as arrays
* `setItem();` overwrites previous values
* `getItem();` will return `nul` if there is nothing stored
* `removeItem();` with remove a value of a key
* `clear();` will delete all the keys and values
* `key();` allows you to see how many values are stored
* can track when storage changes by using an eventListener
* there are limitations to HTML5 storage:
  * only 5 MB of storage space available in browsers
  * "QUOTA_EXCEEDED_ERR" shows up when you go over the 5MB of storage
* HTML5 storage allows you to save your place in a game
  * in the article's example, this is done when changes in a game occur, a function is called to determine if the game has progressed
  * when the page is loaded, a function will determine if the game is still in progress so that it choses to resume the game instead of opening up a new game