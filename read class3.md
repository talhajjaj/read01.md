** Passing Functions as Props**

in react theres a function which is called **map()**,
this function is take an array of numbers and double their values,
and in react transforming arrays into lists of elements is nearly identical.

- If I want to loop through an array and display each value in JSX, how do I do that in React?
well you should build groups of elements and put them in JSX with curly bracts{} , and make a loop through an array by using the java script map
(),
we creat it insid a <ul> element we put insid it <li> elements to return the elements for each item .

- Each list item needs a unique string and key.

- the purpose of a key ,its work  as a hint to react but they don’t get passed to your components. If you need the same value in your component, pass it explicitly as a prop with a different name.
