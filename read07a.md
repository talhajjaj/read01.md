**HTML Tables; JS Constructor Functions**;

Domain modeling;
Domain modeling is the process of creating a conceptual model in code for a specific problem, so Since you'll be modeling the popularity of you'll want to build self-contained objects with the same attributes and behaviors. That way, when you need to change the algorithm for determining popularity, the changes will be small and targeted.
*Tables:*
A table is consisting of row and column
its represents information in a grid format. examples of tables include financial reports, TV schedules.

**Basic Table Structure:**
its start with writting table element, the write the tr element its for table row ,and the td elementfor table data.
Using <th> elements for headings helps people who use screen readers, improves the ability for search engines to index your pages, and also
enables you to control the appearance of tables better when you start to use CSS.
There are three elements that help distinguish between the main content of the table and the first and last rows;
<thead> The headings of the table should sit inside the <thead> element.
<tbody> The body should sit inside the <tbody> element.
<tfoot>The footer belongs inside the <tfoot> element.

**creating an object :**

there is several ways to create objects,
literal notation is the easiest and most popular way to creat objects
the object is the curly braces and thier contents ,the object is stored in a variable,
so you would refer to it as the object .
accessing an object and dot notation:
you access the properties or methodes of an object using dot notation, and we can access properties using squer brackets.

.
creating an object : constructor notation 
you can add properties and methods to the object
you can use syantax to add properties and methods to any object you have created .
to creat an empty object using literal notation use 
curly brackets to creat empty object {}.
updating an object :
to update the value of properties, we use dot notation or square brackets , they work on objects created using literal or constructor notation.to delete a property , use the delete keyword.
creating many objects;
constructor notation ,
somtimes you will want several objects to represent similar things.
object constructors can use a function as a template for creating objects. creat the template with the object's propertes and methods.
you can create instances of the object using the constructor function
the new keyword followed by a call to the function creats anew object , the properties of each object are given as arguments to the function.
arrays are object:
array are actually a special type of object . they hold a related set of key/value pairs (like all objects), but the key for each value is its index number .
arrays of object and objects in array:
you can combain arrays and objects to create complex data structure :
arrays can store a series of object and remember their order. object can also hold arrays (as values of their properties.