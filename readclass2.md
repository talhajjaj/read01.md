**State and Props**

did you know that we can creat a clock component truly reusable and encapsulated. It will set up its own timer and update itself every second!!

by using react and props , but to make it perfect you should use the 'state', so what is state and how to use it currctly?

State it's  similar to props, but it is private and fully controlled by the component, and you should know that first don't modify state directly,instead **use** *setState():* ,
and the only place where you can assign *this.state* is the constructor.
Second ; state updates maybe asynchronous , 
Third ;state updates are merged.

**How to convert a Function to a Class?**

- Create an ES6 class, with the same name, that extends React.Component.
- Add a single empty method to it called render().
- Move the body of the function into the render() method.
- Replace props with this.props in the render() body.
- Delete the remaining empty function declaration.

**Handling Events**
important point:
- React events are named using camelCase, rather than lowercase.
- With JSX you pass a function as the event handler, rather than a string.
- you cannot return false to prevent default behavior in React. You must call preventDefault explicitly.
- When using React, you generally don’t need to call addEventListener to add listeners to a DOM element after it is created. Instead, just provide a listener when the element is initially rendered.
- When you define a component using an ES6 class, a common pattern is for an event handler to be a method on the class.
-  In JavaScript, class methods are not bound by default. If you forget to bind this.handleClick and pass it to onClick, this will be undefined when the function is actually called.
