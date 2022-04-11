# Problem Domain, Objects, and the DOM

## Readings Understanding the problem domain is the hardest part of programming

Understanding the problem is the most critical part of the equation.
You can make the problem easier by cutting out cases and narrowing the focus to a single part of the problem.


## What's the difference between primitive values and objects references in JavaScript?

All data in JavaScript can be put into two categories: Primitive Values and Object References

JavaScript supports eight different data types. 
<li>
    <ol>
    Boolean
    Null
    Undefined
    Number
    BigInt
    String
    Symbol
    Objects -(arrays, functions, dates) Not a primitive data type.
    </ol>
</li>

When a primitive value is assigned to a variable (eg let foo = ‘bar’), the variable is set to that value directly.
When the variable is assigned with an object, however, things are different. Instead of containing the value directly, that variable contains a reference to it.

Primative Values are immutable
Object References are mutable

## Ducket JS, Chapter 3: Object literals pp:100-105

Objects group together a set of variables and functions. 
In an object, variables become known as properties.
In an object, functions become known as methods.
In an object, a name is called a key.


## Ducket JS, Chapter 5: Document Object Model:pp183-242

The DocumenObject Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser.

It is not part of JavaScript or HTML. It is a separate set of rules; making a model of the HTML page and accessing changing the HTML page.

The DOM is an API, Application Programming Interface. 


https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b