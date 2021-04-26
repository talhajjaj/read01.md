#Lists:

you can create lists in HTTML ,with many ways:
- Ordered list: are lists where each item in the list is
numbered , you can write it by useing the <ol> then write <li> inside it to give it a number .
- Unordered lists: are lists that begin with a bullet point,
you can write it by useing <ul> then write <li>

- Definition lists : are made up of a set of terms along with the
definitions for each of those terms.
you should write The definition list is created with the <dl> element and usually consists of a series of terms and their definitions, Inside the <dl> element you will usually see pairs of <dt> and <dd> elements.
*Lists can be nested inside one another.*

#Boxes:
how to handle with boxes ,
- box dimenation : width ,height 
By default a box is sized just big enough to hold its contents. To
set your own dimensions for a box you can use the height and width properties.

- Limiting Width:
 min-width, max-width ,
Some page designs expand and shrink to fit the size of the user's screen.

- Limiting Height:
min-height, max-height
you can control the height of your designs .

- Overflowing content:
The overflow property tells the browser what to do if the content contained within a box is larger than the box itself.

**Border margin and padding** :
Border : Every box has a border (even if it is not visible or is specified to be 0 pixels wide).
margin : Margins sit outside the edge of the border.
padding : Padding is the space between the border of a box and any
content contained within it.
The padding and margin properties are very helpful in adding space
between various items on the page.

- Border Width : 
border-width , The border-width property is used to control the width
of a border.

- The padding property allows you to specify how much space should appear between the content of an element and its border.
- Margin :

The margin property controls the gap between boxes. Its value is commonly given in pixels, although you may also use percentages .
You can specify values for each
side of a box using:
margin-top
margin-right
margin-bottom
margin-left

- Centering Content:
If you want to center a box on the page (or center it inside the element that it sits in), you can set the left-margin and right-margin to auto. 
you can insert it like this,
body {
text-align: center;}

Change Inline/Block :
The display property allows you to turn an inline element into a block-level element or viceversa, and can also be used to
hide an element from the page.
you can add a border to it make it with rounded corner , and make for it a shadows..
