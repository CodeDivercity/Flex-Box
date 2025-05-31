/* Helpful Source: https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-background */

<h2>Properties for the Parent(flex container)</h2>

.container {<br>
  display: flex; | inline-flex (for full width) <br>
  
  gap | row-gap | column-gap: 10px; (for gap between blocks) <br>
  
  flex-direction: row | row-reverse | column | column-reverse; (to line the blocks horizontally or vertically) <br>
  
  flex-wrap: nowrap | wrap | wrap-reverse; (to breakdown line for responsive)<br>
  
  flex-flow: column wrap; <br>
  
  justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly | start | end | left | right ... + safe | unsafe; <br>
  
  align-content: flex-start | flex-end | center | space-between | space-around | space-evenly | stretch | start | end | baseline | first baseline | last baseline + ... safe | unsafe; <br>

  align-items: stretch | flex-start | flex-end | center | baseline | first baseline | last baseline | start | end | self-start | self-end + ... safe | unsafe;
}


<h2>Properties for the Children (flex items)</h2>

.item {
  order: 5; /* default is 0 */ <br>
  
  flex-basis: 100px  | auto; /* default auto */ (Use for block weeight or height) <br>
  
  align-self: auto | flex-start | flex-end | center | baseline | stretch; (For single block movement)
}
