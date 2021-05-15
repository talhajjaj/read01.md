**Images :**
did you know that you can control the size of images ? 

you can change it by using the length and width property in css.

First you need to determine the sizes of images that will be used
commonly throughout the site, then give each size a name. For example:

- small
- medium
- large.

Where the img elements appear in the HTML, rather  than using width and height attributes you can use these names as values for the class
attribute. In the CSS, you add selectors for each of the class names, then use the CSS width and height properties to control the image dimensions.

centering images :

first of all , you should turn it to a block elemnt so you can put it in center.
you can use the text-align property with a value of center.
on the image itself, you can use the use the margin property and set the values of the left and right margins to auto. you can specify class names that allow any element to be centered, in the same way that you can for the dimensions or alignment of images.

Back ground images:
 
background-image property allows you to place an image behind any HTML
element. This could be the entire page or just part of the page. By
default, a background image will repeat to fill the entire box.
you can add it to your web by using css;

p { 
  background-image: url("");},


   you can control background position property to specify where in the browser window the background image should be placed.
   second represents the vertical.

   you can control the position as making it ;

left top

left center

left bottom

center top

center center

center bottom

right top

right center

right bottom.

The background property acts like a shorthand for all of the other background properties you have just seen, and also the background-color property.

background-color.

background-image. 

background-repeat

background-attachment

background-position