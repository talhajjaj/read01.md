**Thinking in React:**


- How would you break a mock into a component heirarchy?

1- The first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names.

2- Use the same techniques for deciding if you should create a new function or object. One such technique is the single responsibility principle, that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

 Separate your UI into components, where each component matches one piece of your data model.

- What is the single responsibility principle and how does it apply to components?

One such technique is the single responsibility principle, that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

- What does it mean to build a ‘static’ version of your application?
to build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. 
 building a static version requires a lot of typing and no thinking.

- What are the three questions you can ask to determine if something is state?

1. Is it passed in from a parent via props? If so, it probably isn’t state.
2. Does it remain unchanged over time? If so, it probably isn’t state.
3. Can you compute it based on any other state or props in your component? If so, it isn’t state.

- How can you identify where state needs to live?

identify every component that renders something based on that state.
Find a common owner component (a single component above all the components that need the state in the hierarchy).
Either the common owner or another component higher up in the hierarchy should own the state.
If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
