HTML5 JavaScript Banner Transition Library
==================

This JavaScript banner animation library intended for use with creating web-based 
animated banners using HTML5's CSS transition capabilties.

One should have a base knowledge of how CSS transitions function in order to be 
able to fully use this library.

Contained within this library are full, but simple examples of how to use this 
JS library for creating an animated banner. BannerTransition.js costs about 6KB 
in file size in the minified form.

This JS library is a bit more involved in what goes in the background. Because 
CSS transitions are simply animating CSS style value changes from the current 
value to the new one, a 50 millisecond timer is implemented to replicate a 
timeline playhead. Every time the timer ticks forward, it checks to see if there 
is a keyframe with style changes to make and if there is, it applies the new 
style value on the target(s) and the browser will handle making the transition 
change.