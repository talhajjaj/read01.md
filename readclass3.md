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


*The Spread Operator;*

so what is the Spread Operator? 

it is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

and we can use it for many task or beniefts lets mention 4 of them :
Copying an array,concatenating or combining arrays, using Math functions,using an array as arguments.

lets give some examples about spread operator;

const newArray = [`1`,`2`,`3`]

const oldArray = [`3`,`2`,`1`]

const ourArray = [...newArray,...oldArray]

- this example is for using the spread operator to combine two arrays.

const fruits = ['🍏','🍊','🍌','🍉','🍍']

const moreFruits = [...fruits];


fruits[0] = '🍑'

- this example it shows of using the spread operator to add a new item to an array.


const hello = {hello: "😋😛😜🤪😝"}

const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}

const helloWorld = {...hello,...world}
console.log(helloWorld)
- example of using the spread operator to add a new item to an array.