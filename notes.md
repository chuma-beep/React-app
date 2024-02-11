<h1>Notes</h1>
<h3>Components:</h3>
<article>

<p>React components are similar to js functions, they're reusable indepent pieces of code. They work indepently and return HTML</p>

 <h5>React component's are of two types:</h5>

 <ol>
    <li>Functional Components</li>
    <h6>Functional components are easier to understand beacause requires less code than Class Components. Hence they are often prefered.</h6>
    <li>Class Components</li>
   <h6>Class components are more verbose, It must include `extends React.Component` and need  `render ` method to return HTML</h6>
  </ol>

<p>
Components can refer to other components in their output. Don't be afraid to split conponents into smaller componets.
Components' names should be <a href="https://www.theserverside.com/definition/Pascal-case"> PascalCase</a>.
You are adviced to think of your app or user interface as a bunch of components 
Elements that need keys should be unique, no-random identifiers.
Methods should be in calmelCase and be named for their function.
Components are dynamic and contain something called state.</p>
   <h2>State</h2>
   This is likes a components memory, this determines how a componet renders and behaves. it lets a component keep track of some information and change it in response to interactions. 
    i. componets have App or Global state. these are availbale to the entire UI and Not just as single component.
    prior to React 16.8 , we had to use class based components to use state. 
    Now we can use functional components with hooks
  <h2>React Hooks</h2>
       <p>these are functions that let us hook into React state and lifecycle faeatures from function components</p>

    . useState- Returns a stateful value and a function to update it
    . useEffect - Perform side effects in function comnponets 
    . usecontext, useReducer, useRef - Beyond the scope of this course
    
 

<h3>Things to note about JSX</h3>
 . expressions in jsx mush have one parent
 . what ever you return must have a single parent and other components must go inside it.


<h3>PropTypes:</h3>
  PropTypes is a a method you can use to ensure that the datatype is correct for each prop.


<h3>Props (properties)</h3>
   Props are like arguements you pass to a function
   -to retrive props in your components you take in props as your parameter. this is similar to how arguments are passed in a fucntion.
   -props make components resuable as they pass data from one component to another.
   -props acts as a channel for component communication.
   -props are passed to help properties be accessed if they make it to another parent tree. 




<h3>Styling a react app:</h3>
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