# React Boilerplate

### Under the Hood
Technologies used: </br>
```
['Axios', 'Babel', 'Express', 'React', 'Redux', 'Webpack'];
```

### Up & Running
Follow these two simple steps to initialize the application locally on your computer to start coding in minutes.</br>
1. `npm install` **->** Installs dependencies. Babel, React, etc.
2. `npm start` **->** Starts node server and spins up Webpack for file compilation and hot reload.

### Client Code Architecture
`index.jsx` **->** Root file for the React application. Initializes the Redux store, routes, etc.</br>
`actions`  **->** Actions to be dispatched based on user events. Logging in, creating an account, etc.</br>
`assets`  **->** Global assets required throughout the application. Sass mixins, variables, etc.</br>
`components`  **->** Global components to be reused throughout the application. For example, a container component for responsiveness architecture.</br>
`reducers`  **->** Initial state for the redux store.</br>
`routes`  **->** Routes for the application.</br>
`scenes`  **->** Also known as pages. Scenes are the components to be displayed via routes. For example, the login route will display the login scene, etc.</br>

```
├── index.jsx
├── actions
|  └── ...
├── assets
|  └── ...
├── components
|  └── ...
├── reducers
|  └── ...
├── routes
|  └── ...
└── scenes
   └── ...
```
