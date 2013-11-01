jQuery-kbAnim
=============

Here the intro to the software should have been, the bugs ate it.

http://en.wikipedia.org/wiki/Ken_Burns_effect

This plugin is supposed to make it easy to replace one image with another in nice way.

With jQuery we can change images with ease, now we can also do it in style.

example:

html:
<img id=image1 src="example1.jpg">
<script>
jQuery(function($){
  $('#image1').animate({src:'example2.jpg'},500,{effect:'kenburns'});
});
