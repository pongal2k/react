# React
## Basic
* React is a javascript library
* Show content and handle user interaction

### Installation
* Install/Update Node JS
* Install create-react-app ```npm i -g create-react-app`
* create-react-app <name_of_project>
* ```npx create-react-app <name>```

#### Project Structure
* src - source files
* public - static files like images

* npm start to start running the react applications
* delete all files in src folder
* create a file index.js
  * import react and reactdom libraries
  * ```import React from 'react'; import ReactDOM from 'react-dom'```
  * create a react component
  * take react component and show it on screen
  
A react component is a function or a class that produces html to user and handles feedback from user using event handlers
```
const App = () => {
  return <div>Hi there!</div>
}
```

```
ReactDOM.render(<App />, document.querySelector("#root"));
```
 ## JSX vs HTML
 ```<div style={{ backgroundColor: 'red' }}></div>```
 ```<label className="label">Enter name</label>```
 ```
 const buttonText = "submit"
 in jsx... {buttonText}
 ```
 
 Good practice to keep console open and look for any error messages
 
 ### Tenants of Component
 * Component nesting
 * Component Reusability
 * Component Configuration
 
* Semantic UI for styling
* Faker js to generate fake data
 
### Props
System for passing data from a parent component to a child component. Goal is to customize or configure a child component.

If a component/text/jsx is sent as a children of another component, use props.children in the child component.

### Class based component
Functional components are for simple content, Class based for everythign else

Class based components are:
* Easier to organize code
* Can use state, easier to handle input
* Understands life cycle events, easier to do things when the app first starts




 
 
