This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

In this app we will see how to use Polymer elements in a React project.

## Init polymer elements

To use Polymer elements in your React application, you must implement Polymer elements in the public folder of the React application!

##### `cd public && polymer init`

After creating your polymer element, import it into the `index.html` file

`<link rel="import" href="src/my-main-element/my-main-element.html">`

And now, you just need to use your element in your React component (in our case we used it in the `App.js`)

`function App() { return ( <my-main-element"></my-main-element> ); }`

## Run your app

##### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.
