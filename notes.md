<h1>Notes</h1>
<h3>Components:</h3>
<article>

<p>React components are similar to js functions, they're reusable indepent pieces of code. They work indepently and return HTML</p>

 <h5>React component's are of two types</h5>:
 <ol>
    <h6>Functional Components</h6>
    <h6>Class Componnents</h6>
  </ol>
<p>
Components can refer to other components in their output. Don't be afraid to split conponents into smaller componets.
Components' names should be <a href="https://www.theserverside.com/definition/Pascal-case"> PascalCase</a>.
You are adviced to think of your app or user interface as a bunch of components 
Elements that need keys should be unique, no-random identifiers.
Methods should be in calmelCase and be named for their function.
Components are dynamic and contain something called state.</p>
   <h4>State</h4>
   This is likes a components memory, this determines how a componet renders and behaves. it lets a component keep track of some information and change it in response to interactions. 
    i. componets have App or Global state. these are availbale to the entire UI and Not just as single component.
    prior to React 16.8 , we had to use class based components to use state. 
    Now we can use functional components with hooks
React Hooks
       these are functions that let us hook into React state and lifecycle faeatures from function components

    . useState- Returns a stateful value and a function to update it
    . useEffect - Perform side effects in function comnponets 
    . usecontext, useReducer, useRef - Beyond the scope of this course
    
 

*Things to note about JSX
 . expressions in jsx mush have one parent
 . what ever you return must have a single parent and other components must go inside it.


PropTypes:
  PropTypes is a a method you can use to ensure that the datatype is correct for each prop.


Props (properties)
   Props are like arguements you pass to a function
   -to retrive props in your components you take in props as your parameter. this is similar to how arguments are passed in a fucntion.
   -props make components resuable as they pass data from one component to another.
   -props acts as a channel for component communication.
   -props are passed to help properties be accessed if they make it to another parent tree. 




Styling a react app:
   -You can use css.
     .css in js
     .css modules
     .css preprocessors
     .css frameworks
   -You can use component Libraries
    
###
note that app.js is the .........
###

sources for more learning:
https://www.youtube.com/watch?v=w7ejDZ8SWv8&t=4138s
https://react.dev/learn/thinking-in-react

</article>