# Valentine Scratch Card

This is a little fancy Valentine's Day scratch card widget. What's needed is a HTML/CSS placeholder, followed by some JavaScript magic.

## HTML/CSS
The main area is a div with the attached picture as a background image. It is covered totally by several smaller square divs, red in color and at full opacity. All JavaScript actions take place on mouseover on these smaller gifs.

## JavaScript
Upon mousover, target the div moused over, and all its surrounding divs. The div that is moused over will be set to **fully transparent**.

For the surrounding divs...

If the div is in **full opacity**, change it to **half opacity**.
If it is already at **half opacity**, change it to **fully transparent**.

