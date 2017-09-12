# AHHH! Grid!!

## Resources

http://cssgridgarden.com/

https://gridbyexample.com/

http://jensimmons.com/post/aug-15-2017/heres-super-quick-way-try-out-css-grid

https://aneventapart.com/news/post/css-grid-layout-by-rachel-andrewan-event-apart-video

https://cssgrid.cc/

http://csskarma.com/blog/css-grid-layout

https://rachelandrew.co.uk/css/cheatsheets/grid-fallbacks

## The Basics

display: grid;

grid-template-rows: % em px;

grid-template-columns: % em px;

**grid-template: row row row / column column column;**
- repeat function "repeat(8, 12.5%)"

--

grid-row-start:

grid-row-end:

grid-row: start / end;

grid-column-start:

grid-column-end:

grid-column: start / end;

**grid-area: grid-row-start / grid-column-start / grid-row-end / grid-column-end;**
- number and span  keyword "span 2"

--

order: 
- default is 0
- can be set to any positive or negative value

--

grid-row-gap:

grid-column-gap:

**grid-gap: grid-row-gap grid-column-gap**
