**Object Literals:**
Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object,variables and functions take on new names.

creating an object literal notation; creating an object literal notation literal notation is the easiest and most popular way to creat object,the object is stored in variable ,so you can refer to it. 
If you had two objects on the same page, you would create
each one using the same notation but store them in variables with different names.

**Document Object Model** 
(DOM) The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. It is implemented by all major browser makers.
the dom tree is amodel of a web page,As a browser loads a web page, it creates a model of that page.the model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes ;
![photo](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/DOM-model.svg/1200px-DOM-model.svg.png)

working with the dom tree :
- first of all access the elemnts
- work with those elements.

.
caching dom queries ; 
methods that find elemnts in the DOM tree are called DOM queries.
when you need to work with an element more than once , you should use a variable to store the result of this query.

Selecting elements using id attributes;
get El ementByid () al lows you to select a single element node by specifying the value of its id attribute.
This method has one parameter:
the value of the id attribute on the element you want to select. This value is placed inside quote marks because it is a string. The quotes can be single or double quotes, but they must match.

selecting an element from a nodelist ;

There are two ways to select an element from a Nodelist:
The item() method and array syntax. Both require the index number of the element you want.
Array syntax is preferred over the item() method because it is faster.before selecting a node from a nodelist , check that it contains nodes . if you repeatedly use the Nodelist ,store it in a variable.

Repeating actions for an entire noodelist;

when you have Nodelist,you can loop through each node in the collection and apply the same statements to each.

attribute nodes ;
once you have an element node, you can use other properties and methods on that element node to access and change its attributes.