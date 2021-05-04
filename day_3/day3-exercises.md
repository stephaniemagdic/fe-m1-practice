# Chapter 7: Forms

If you're using an input element in a form, what attribute controls the behavior of that input?

- I am not sure if I am reading this question right, but I believe the type attribute controls the behavior of that input. It allows you to choose what kind of <input> element to display.


What element is used to create a dropdown list?

- To create a dropdown list, a <select> element is used.


If you're using an input element to send form data to a server, what should the type attribute be set to?


- I am not sure if I am reading this question correctly either, but I believe that when you are using an input element and we are sending information to the server we need to first make sure the action attribute's value is the URL for the page on the server that will receive the information in the form when it is submitted and then the method would be a get or post depending on several factors. (pg.151)


What element is used to group similar form items together?


- The <fieldset> attribute is used to group similar form items together.


# Chapter 13 & 15: Boxes and Layout


Describe the differences between border, margin, and padding.


- _border_:The border separates the edge of one box from another (The box: remember that CSS treats each HTML element as if it lives in its own box).
- _margin_:Margins sit outside the edge of the border and it creates a gap between the borders of two adjacent boxes (if you want it to)
- _padding_:Padding is the space between the border of the box and any content contained within it

(pg. 307)


For a CSS rule padding: 1px 2px 5px 10px, what sides of the content box does each pixel value correspond to?


- CSS rule padding: padding-top, padding-right, padding-bottom, padding-left (clockwise from the top)


Describe the difference between block-level and inline elements.


- lock-level elements start on a new line and act as the main building blocks of any layout while inline boxes flow between surrounding texts.

  Examples of block level elements include <h1>, <p>, <ul>, and <li>.
  Examples of inline elements include <img>, <b> <i>.


What is the role of fixed positioning, and why is z-index important in the scenario of using fixed positioning?


- A fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed. The difference from absolute is that it stays in one place when the user scrolls. If I understand this correctly, it has an absolute position in that it doesn't affect other elements and it is taken out of the normal flow, and it is also _fixed_ in place when scrolling.


What is the difference between a fixed and liquid layout?


- A fixed (width) layout design does not change size as the user increases or decreases the size of their browser window. (Measurements tend to be in pixels)

- Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window (and they tend to use percentages).
