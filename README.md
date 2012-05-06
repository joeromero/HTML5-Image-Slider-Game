#HTML5-Image-Slider-Game

Split image into puzzle pieces (and display in random order) and let user move pieces back together again.

Works on mobile and desktop devices devices (using mouse and touch events).

**Checkout the drag and drop branch - still being worked on**

##TODO (Bugs):
* touch device issues:
    * animation of pieces (on iPad only) isn't correct (e.g. clearRect) as you can see thin lines where puzzle piece not removed properly
    * somehow prevent iOS devices from showing 'copy' tooltip when double-tapping from selected canvas 

##TODO:
* Work out when all the pieces are in the correct place and signal to the user that the game is finished
* JShint the shiznit out of the code (hopefully wont be too tragic)
	
##TODO (feature):
* Create handle icons (or think up unique way to allow) for whole rows/cols to be dragged at once
* Swap out setInterval for requestAnimationFrame polyfill