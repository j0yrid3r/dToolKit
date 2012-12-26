dToolKit
========
A set of jQuery functions for designers<br/>
What is it? Most of them are css(3) settings called using jQuery.<br/>
How to use? Include <strong>assets/js/jquery.dtoolkit.min.js</strong> in your page (after jquery itself)<br/>
<br/>
All examples can be found in index.html<br/>
<br/>
<strong>V0.1</strong><br/>
<br/>
<strong>Border radius</strong><br/>
tl = top left corner / tr = top right corner / br = bottom right corner / bl = bottom left corner<br/>
<code>$('.sDiv').bRadius({tl:20,br:40});</code><br/>
<br/>
<strong>Scrolling</strong><br/>
Scroll to bottom / top, create an element at the top of the page and one on the bottom of the page and fill them in below<br/>
<code>$('.scrollBottom').scrollBottom();</code><br/>
<code>$('.scrollTop').scrollTop();</code><br/>
<br/>
<strong>Background color</strong><br/>
Rainbow cycle background of any element. To change the color scheme, change it in <strong>assets/css/dtoolkit.css</strong><br/>
<code>$('.mDiv').cycleBGColor({sec:20});</code><br/>
<br/>
Daily background color change on two weekly basis (max: 14 colors c1 - c14). Have a different background color every day. 1 set of colors for the even weeks (c1 - c7) and a 2nd set of colors for the odd weeks (c8 - c14)<br/>
<code>$('body').coloredBG({c4:'ffcc00',c5:'000000'});</code><br/>
<br/>
<strong>Bounce element</strong><br/> 
times = amount of bounces / distance = height of bounce / speed = speed of bounce<br/>
<code>$('.fDiv').bounceElement({times:5, distance:90, speed:300});</code><br/>
<br/>
<strong>Rotate element</strong>
Rotate elements to a fixed degree<br/>
<code>$('.fDiv').fixedRotate({degrees:200});</code><br/>
<br/>
Rotate elements random to predefined degrees (16 options r1 - r16, positive and negative values)<br/>
<code>$('.sDiv').randomRotate({r1:70,r2: -200,r3: 10, r4: -88});</code><br/>
<br/>
Rotate elements with animation, degrees = amount of degrees / duration = speed of animation<br/>
<code>$('.mDiv').animateRotate({degrees:300,duration:8.0});</code>
