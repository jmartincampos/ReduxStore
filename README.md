## Redux Store Implementation for E-commerce Platform
This project implements Redux for managing global state in an e-commerce platform. The goal is to refactor the existing application to use Redux instead of the Context API for state management.

## Overview
In this project, we leverage Redux, a powerful state management library for React applications, to handle complex state management requirements in the e-commerce platform. Redux provides a predictable state container that allows us to manage the application's state in a more organized and scalable manner.

## Background
Traditionally, React developers have used the Context API for managing global state. While the Context API is useful for simpler applications, Redux shines in managing complex state requirements, especially in large-scale applications like e-commerce platforms.

## User Story
As a senior engineer working on an e-commerce platform, I want my platform to use Redux to manage global state instead of the Context API so that my website's state management is taken out of the React ecosystem.

## Acceptance Criteria
The app's store should use Redux instead of the Context API.
The app should use a Redux provider to access the Redux store.
Reducers should be passed to the Redux store to determine changes to global state.
The app should extract state data from the Redux store.
Actions should be dispatched using Redux.
Getting Started
To run the application locally, follow these steps:

## Clone the repository: https://github.com/jmartincampos/ReduxStore.git
Install dependencies using npm install.
Start the development server using npm run dev.
Open the application in your browser at http://localhost:3000.

## Folder Structure
The project follows a standard folder structure for a React application with Redux:

src/actions: Contains action creators for Redux actions.
src/components: Contains React components.
src/reducers: Contains Redux reducers for managing state changes.
src/store: Contains the Redux store configuration.
src/index.js: Entry point of the application.
src/App.js: Main component rendering the application.
Deployment
To deploy the application to Render, follow these steps:

Create a Render account if you haven't already.
Set up a new static site on Render.
Connect your GitHub repository to Render.
Configure the build settings to run vite build.
Trigger a manual or automatic deployment from the Render dashboard.
Testing
Unit tests for components, actions, and reducers can be written using Jest and Enzyme. Run npm test to execute the tests.

## Conclusion
By implementing Redux in the e-commerce platform, we ensure more scalable and maintainable state management. Redux provides a centralized state container that simplifies state management in large-scale applications.

Feel free to explore the codebase and provide feedback or suggestions for improvements. Your contributions are highly appreciated!

- - - - - 

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
