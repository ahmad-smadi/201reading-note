# layout 
## controlling the position of element 

### normala flow 
* position: static;

- when I have not specified a width property for the heading element, so you can see how it
stretches the width of the entire browser window by default

### relative position 

* position:relative

-  Relative positioning moves an element in relation to where it would have been in normal flow


### absolute positing 

* position:absolute


- When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.)

### fixed positioning

* position:fixed

- It positions the element in relation to the browser window. 
Therefore, when a user scrolls down the page, it stays in the exact same place

### overlapping elements 


* z-index

- If you want to control which element sits on top, you can use the z-index property


### floating elements 

* float 
The float property allows you to take an element in normal flow and place it as far to the
left or right of the containing element as possible.


### clearing floats 

* clear 
- The clear property allows you to say that no element (within the same containing element)
should touch the left or righthand sides of a box. It can take the following values:

- left : The left-hand side of the box should not touch any other elements appearing in the same containing element
- right : The right-hand side of the box will not touch elements appearing in the same containing element.
- both : Neither the left nor right-hand sides of the box will touch elements appearing in the same containing element
- none : Elements can touch either side