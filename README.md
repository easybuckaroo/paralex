Paralex

Lightweight Parallax simiar effects. Can be placed under any HTML element.
Sizes: Third, Half, Full screen. Area will auto-expand to forground text size.

Scroll Speed: Slow, Medium, Fast. Changes size of background image, effect of moving at different rates.

Background effect: Scroll with mouse, Scroll Reverse of mouse, Fixed background

Background inline styles: background, background-position, opacity

Background position is a focal point, when the background image is cropped to fit in area, cropped image will focus on the background position.

Opacity: 0.3 is nice for dark text.
  &lt;div class=&quot;paralex (default:third|half|full) (slow|default:medium|fast) (default:scroll|reverse|fixed)&quot;&gt;
    div class=&quot;background&quot; style=&quot;  (everthing except background: url is optional)
       background: url('https://...');
       opacity: 0.3;
       background-position: center center; /*OR*/
       background-position-x: 50%;
       background-position-y: 50%;
       &quot;&gt;
    &lt;/div&gt;
    &lt;div class=&quot;foreground&quot;&gt;
     Content Content Content	
    &lt;/div&gt;
  &lt;/div&gt;
  
If you need assistance dbrabon@gmail.com
