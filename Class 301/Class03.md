#Class 03: Passing Functions as Props

## Lists and Keys

What does .map() return? An array
If I want to loop through an array and display each value in JSX, how do I do that in React? Wrap it in curly braces.
Each list item needs a unique ____. Each liste item needs a unique Key.
What is the purpose of a key? A key helps react identify what items have changed, added and are removed.

## The Spread Operator

What is the spread operator? It is thre dots ... and expands an iterable object into a list of arguments.
List 4 things that the spread operator can do. Copying an Array, Using Math Functions, Adding an Item to a list, Combining Objects
Give an example of using the spread operator to combine two arrays. 
const fruits = ['ð','ð','ð','ð','ð']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "ð", "ð", "ð", "ð", "ð" ]
fruits[0] = 'ð'
console.log(...[...fruits,'...',...moreFruits]) //  ð ð ð ð ð ... ð ð ð ð ð

Give an example of using the spread operator to add a new item to an array.
const fewFruit = ['ð','ð','ð']
const fewMoreFruit = ['ð', 'ð', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "ð", "ð", "ð", "ð", "ð" ]

Give an example of using the spread operator to combine two objects into one.
const myArray = [`ðĪŠ`,`ðŧ`,`ð`]
const yourArray = [`ð`,`ðĪ`,`ðĪĐ`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // ðĪŠ ðŧ ð ð ðĪ ðĪĐ

## How to Pass a Function Between Components

In the video, what is the first step that the developer does to pass functions between components?
The developer types out increment he wants to pass up.

In your own words, what does the increment function do?
Increment updates the State.

How can you pass a method from a parent component into a child component?
You call the method from the parents with something like 'this.props.increment()'

How does the child component invoke a method that was passed to it from a parent component?
It calls the name from the parent component .

## Things I want to know more about.
Until I type this out an use it, reading and listening to the video doesn't make much sense to me.


#### All credit to the following links
https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab