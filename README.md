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
