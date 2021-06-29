# React 1

### About React
- React is a JavaScript library for building user interfaces.
- React is used to build single page applications.
- React allows us to create reusable UI components.

### Create React App

1. In order to learn and test React, you should set up a React Environment on your computer.

2. The create-react-app is an officially supported way to create React applications.

3. If you have NPM and Node.js installed, you can create a React application by first installing the create-react-app.

4. Install create-react-app by running this command in your terminal by using: 
  - npm install -g create-react-app
5. You are now ready to create your first React application!
6. Run this command to create a React application, let is call is example:
  - npx create-react-app example
7. The create-react-app will set up everything you need to run a React application.

### To Run the React Application
1. Run this command to move to the example directory:
2. cd example
3. Run this command to execute the React application example:
4. npm start
5. Now open your browser and type localhost:3000 in the address bar to see the output.

### What is JSX?
- JSX stands for JavaScript XML.
- JSX allows us to write HTML in React.
- JSX makes it easier to write and add HTML in React.

### Why JSX?
- React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display.

- Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both. We will come back to components in a further section, but if you’re not yet comfortable putting markup in JS, this talk might convince you otherwise.

- JSX allows us to write HTML elements in JavaScript and place them in the DOM without any createElement()  and/or appendChild() methods.

- JSX converts HTML tags into react elements.
