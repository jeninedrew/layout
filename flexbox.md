# Flexbox

## Resources

http://flexboxfroggy.com/

https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties

## The Basics

display: flex;

justify-content: 
- flex-start
- flex-end
- center
- space-between
- space-around

--

flex-direction: (aligns flex items along the main axis)
- row
- row-reverse
- column
- column-reverse
- FYI when you set the direction to a reversed row or column, start and end are also reversed.

flex-wrap: (specify whether flex items are 
- nowrap
- wrap
- wrap-reverse

flex-flow:
- the combo of flex-direction and flex-wrap
- accepts two values

--

align-items:
- flex-start
- flex-end
- center
- baseline
- stretch

align-content:
- flex-start
- flex-end
- center
- space-between
- space-around
- stretch

align-self:
- flex-start
- flex-end
- center
- baseline
- stretch

order:
- By default, items have a value of 0
- Set a poitive or negative integer value
