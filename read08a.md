**Layout:**


how to creat attractive page layouts , 
key concepts in postining elements
building blocks
css treats each HTML elemnts as if it is in its own box.the box will be inline box or a block level , Block-level boxes start on a new line and act as the main building blocks
of any layout, while inline boxes flow between surrounding text.
Block level elements examples: <h1> <p> <ul> <li>
.

inline elements: <img> <b>.
if one block level element sits inside another block level element then the outer box is known as the containing or parent element.
controlling the position of elements: 

there is three ways to use the property in CSS;

- Normal flow : Every block-level element
appears on a new line.

- Relative positionig ; This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed.
- Absolute positioning:
This positions the element in relation to its containing element.

we can use box offset properties to tell the browser how far from the top or bottom ..
- Fixed positioning : 
This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element.
Floating elements;

- Floating an element allows you to take that element out of normal flow and position
it to the far left or right of a containing box.
clearing floats : the clear property allows you
to say that no element (within the same containing element) should touch the left or righthand sides of a box.
creating multi columnm layouts with floats:
there is many properties are used to position the columns :
width ;to sets the width of the columns .
float : to make columns next to each other .
margin : to creat gap between columns .

**screen size :**
 your site will have different sized screens that show
different amounts of information,so your design needs to be able to work on ,the size of a user's screen affects how big they can open
their windows and how much of the page they will see, and its count on resolution refers to the number of dots a screen shows per inch.

fixed width layouts
it designs to dont change size as the user increases or secreases the size of their browser window,
there is a dvantages :
- you can control the lengths of lines of text regardless of the size of users window .
- the size of an image will always remain the same relative to the rest of the age .
Disadvantages:
you can end up with big gaps around the edge of a page .
if the user increases font size ,text might not fit into the allotted spaces
.

.
liquid layout designs stretch and contract as the user increases or decreases the size of the browser window 
Advantages;
- Pages expand to fill the entire browser window so there are no spaces around the page on a large screen.
- If the user has a small window, the page can
contract to fit it without the user having to scroll to the side.
liquid layout designs stretch and contract as the user increases or decreases the size of the browser window 
Advantages;
- Pages expand to fill the entire browser window so there are no spaces around the page on a large screen.
- If the user has a small window, the page can
contract to fit it without the user having to scroll to the side.
disadvanteges:
- If the user has a very narrow window, words may be squashed and you can end up with few words on each line.
-  If a fixed width item (such as an image) is in a box that is too small to hold it (because
the user has made the window smaller) the imagecan overflow over the text.