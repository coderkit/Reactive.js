<div style="text-align:center;"><img src="https://github.com/coderkit/Reactive.js/blob/master/reactive.png" style="width:128px;height:128px"></div>

*Reactive js is a library used to do flip animation with the value inside HTML elements* 

  Features:
  
    - Flip up, right, left and down
    - Flip up and down, right and left and reverse
  Usage:
  
      General usage   = reactive.flipway(element name, animation time, word to change);
      flipway         = flipUpPx, flipDownPx, flipLeftPx, flipRightPx, flipVerticalUp, flipVerticalDown, flipHorizontalUp, flipHorizontalDown
      element name    = name of the element you want to flip
      animation time  = configure the time that the animation will take place
      word to change  = word that will be flip when the animation start
          Example: reactive.flipUpPx('#demo', 300, 'DEMO');
          
  Multiple animation:
  
  			//Example:
  					reactive.flipUpPx('#demo', 300, 'NOT ANYMORE');
            function second () {
            reactive.flipUpPx('#demo', 300, 'Why not?');
            }
            function third() {
            reactive.flipVerticalUp('#demo', 300, 'Cause it\'s cool');
            }
            window.setTimeout(second, 1500);
            window.setTimeout(third, 2500);
       
            //Set timeout for function to perform multiple animations.
            
            
            
            // See demo at: reactivejs-demo.gweb.io
  
