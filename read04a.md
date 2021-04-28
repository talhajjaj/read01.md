**Links:**

*what is links do for your website?*
its let you to move from page to another and help you to open new resources.
*how to write links in your Html?*
you can creat links using the  <a> element </a>, and but the link that you want to add between them it will looks like this :
<a href="the link">text link</a>
the text link it what will appear in user screen it should be a keyword for the link and be specific .
can i link other sites with my page ?
yes sure, by useing the <a> element you can copy the url of the site that you want to linked , then copy it between cotation ,write the name of the site in text link to make the user see it .

Linking to other pages on the same site:
When you are linking to other pages within the same site,you only need to use a relative url . These are like a shorthand version of absolute URLs because you do not need to specify the domain name , its a way of telling the browser where to find your files and its quicker to write .
The main homepage of the entier site written in HTML, and the default name for new file its index.html.
Every page and every image on a website has a URL, The URL is
made up of the domain name followed by the path to that page or image.

when you write the relative links you will use the slashes ,forward slash will return the homepage for the entire site,and a forward slash followed by a file name will return that file providing it is in the root directory

how to link a e-mail to your site ?
by using mailto keyword , To create a link that starts up the user's email program and addresses an email to a specified email address, you use the <a> element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.

how to opining links in new window ?
you can use the 'target' attribute on the opening <a> tag.
<a href="http://" target="">

how to linking it to a specific part of same site :
You do this using the id attribute ,the value of the id attribute
should start with a letter or an underscore (not a number or any other character) and, on a single page, no two id attributes should have the same value.
To link to an element that uses an id attribute you use the <a> element again, but the value of the href attribute starts with the # symbol, followed by the value of the id attribute of the element you want to link to.
 <a href="#hi">

 Linking to a specific part of another page;
 the href attribute will contain the address for the page (either an absolute URL or a relative URL), followed by the # symbol, followed by the value of the id attribute that is used on the element you are linking to.
 <a href="http/#bottom">

 **Layout:**
 Key concepts in positioning elements;
 Building blocks CSS treats each HTML element as if it is in its
own box. This box will either be a block-level box or an inline box.
block element is : <h1> <p> <ul> <li>
Inline elements is :<img> <b> <i>
If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

Controlling the position of elements : 
CSS has the following positioning schemes that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.

To indicate where a box should be positioned, you may also need to use
box offset properties to tell the browser how far from the top or bottom and left or right it should be placed.

Fixed Positioning:
This is a form of absolute positioning that positions the element in relation to the browser window.do not affect the position of surrounding elements and theydo not move when the user scrolls up or down the page.
Floating Elements: floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box.

Normal flow, each block-level element sits on top of the next
one.
Relative positioning moves an element in relation to where it would have been in normal flow.
code in CSS : position:relative
absolute position:
When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page.
code in CSS : position:absolute