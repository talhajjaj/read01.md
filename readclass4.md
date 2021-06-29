**React and Forms**


- well, what is a ‘Controlled Component’?

We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.


- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

we should update the state with their responses as soon as they enter them,so it will keep updating.

- How do we target what the user is entering if we have an event handler on an input field?

whith target element 

When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.

***The Conditional (Ternary) Operator Explained***


Why would we use a ternary operator?

The ternary operator greatly increases the conciseness of your code. When it is formatted correctly it can also be very easy to read and, dare I say it, even easier then if-else statements.
and because it take less time and effort .

(the link didnt opened so i take the information from( http://www.dnawebagency.com/ternary-operator/))
