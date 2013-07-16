smint-extended
==============

This is a plugin written by Robert McCracken (twitter: @rabmyself). I added some code to provide links within the menu without the scrolling functionality.
If you have a link like ```<a href="#" id="do-not-scroll">Do not scroll</a>``` and you omit the ```<div class="section do-not-scroll"></div>``` you get an error.
With this version of SMINT you can just add the class smint-disable to your link like this ```<a href="#" id="do-not-scroll" class="smint-disable">Do not scroll</a>``` an everything is find.
