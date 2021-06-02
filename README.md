# scrollToTop
This is my version of "scroll to the top" jQuery plugin. 

## To use this plugin

```
<script type="text/javascript" src="jquery.js"></script>

<script type="text/javascript" src="scrollToTop.js"></script>
```
Place this 
`````````
$("body").scrollToTop({
  position: "bottom-right", //top, top-left, top-right, bottom, bottom-left or bottom-right of the screen
  upwards: 0, //distance from the current postion upwards
  downwards: 0, //distance from the current postion downwards
  toTheLeft: 0, //distance from the current postion to the left
  toTheRight: 0, //distance from the current postion to the right
  elementTop: "", //the element with which you want the "back to the top" to appear when the scrollbar reaches it
  scrollTop: 100, //how many number of pixels from the top when the scroll bar moves do you want the button to appear
  scrollSpeed: 100, //speed of the scrolling up animation
  beforeScroll: function() {}, //custom function before scrolling up
  afterScroll: function() {} //custom function after scrolling up
});

`````````

inside
```
$( document ).ready(function() {
    //here
});
```
