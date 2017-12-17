# Flexbox

## Resources

https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties

https://www.sketchingwithcss.com/samplechapter/cheatsheet.html

https://geddski.teachable.com/p/flexbox-zombies

https://madebymike.com.au/demos/flexbox-tester/

https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties

https://medium.freecodecamp.org/the-ultimate-guide-to-flexbox-learning-through-examples-8c90248d4676

https://medium.freecodecamp.org/understanding-flexbox-everything-you-need-to-know-b4013d4dc9af

http://flexboxfroggy.com/

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
