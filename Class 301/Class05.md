# Putting it all Together

## Thinking in React

1. What is the single responsibility principle and how does it apply to components?
    a. It is having a component only do one thing.

2. What does it mean to build a ‘static’ version of your application?
    a. That the application will not change over time.

3. Once you have a static application, what do you need to add?
   a. 

4. What are the three questions you can ask to determine if something is state?
   a. Is it passed in from a parent via props? If so, it probably isn’t state.
   b. Does it remain unchanged over time? If so, it probably isn’t state.
   c. Can you compute it based on any other state or props in your component? If so, it isn’t state.

5. How can you identify where state needs to live?
    a.For each piece of state in your application:
        1. Identify every component that renders something based on that state.
        2. Find a common owner component (a single component above all the components that need the state in the hierarchy).
        3. Either the common owner or another component higher up in the hierarchy should own the state.
        4. If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.


## Higher-Order Functions

1. What is a “higher-order function”?
    a. Functions that operate on other functions, either by taking them as arguments or by returning them.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
    a.  It is returning M as long as M is greater than N.

3. Explain how either map or reduce operates, with regards to higher-order functions.
    a.Map applies a function to the array and then building a new array from the original values.

## Things I want to know more about
    I want to find a list of all the Higher-Order functions, or maybe a cheat sheet for using them.

#### Resources

1. https://reactjs.org/docs/thinking-in-react.html
2. https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK
