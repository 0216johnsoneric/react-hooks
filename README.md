# React Setup

1) npx create-react-app
2) cd into project
3) set up src folder components and js files
4) link bootstrap in public/index.html 
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.0.0/css/bootstrap.min.css"/>
5) npm install react-bootstrap bootstrap    
6) npm install axios
7) npm install react-router-dom

In this activity we will practice using the useContext Hook in React by creating a global state for our articles.

  # Instructions

  * Replace your React application's src folder with [Unsolved/src](Unsolved/src).

  * Start the application in dev mode by running `npm start` in your terminal.

  * Open your browser to [localhost:3000](http://localhost:3000) and study the rendered application.

  * Update this application to accomplish the following:

  * Combine all of the `useState` Hooks that are relevant to the information retrieved from the Wikipedia article into a single `useState` Hook.

  * Create a Context Object that will be used to store the state of the article called `ArticleContext`.

  * Wrap the components that will need access to the Context Object with a Context Provider.

  * Update the `SearchResults` component with the `useContext` Hook to to eliminate the need for props.