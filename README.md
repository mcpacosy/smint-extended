smint-extended
==============

SMINT [(Website)](http://www.outyear.co.uk/smint/) is a jQuery plugin written by Robert McCracken (twitter: @rabmyself). I added some code to provide links within the menu without the scrolling functionality.
If you have a link like ```<a href="#" id="do-not-scroll">Do not scroll</a>``` and you omit the ```<div class="section do-not-scroll"></div>``` you get an error.
With this version of SMINT you can just add the class smint-disable to your link like this ```<a href="#" id="do-not-scroll" class="smint-disable">Do not scroll</a>``` an everything is fine. Full example:

```
<div id="menu">
    <a href="#" id="somthing-else" class="smint-disable">Do something else</a>
    <a href="#" id="section-1">Section 1</a>
    <a href="#" id="section-2">Section 2</a>
    <a href="#" id="section-3">Section 3</a>
    <a href="#" id="section-4">Section 4</a>
</div>

<div class="section section-1">
   ... 
</div>

<div class="section section-2">
   ... 
</div>

<div class="section section-3">
   ... 
</div>

<div class="section section-4">
   ... 
</div>
```
