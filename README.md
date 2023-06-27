# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Technoligies & Tools
* VSCode
* JavaScript
* React
* TailwindCss

## Some Steps / Terminal Commands
* Create the project folder locally
* cd to your project
* npm create react-app . (This will create the necessary files and folder for the project)
* npm install -D tailwindcss postcss-cli autoprefixer
* create tailwind.js (project level)
* create a folder: assest
* create 2 files in assest folder: main.css and tailwind.css
* npx tailwind init tailwind.js --full
* create a file (project level): touch postcss.config.js
* update package.json file
    "scripts": {
      "start": "npm run watch:css && react-scripts start",
      "build": "npm run buld:css && react-scripts build",
      "test": "react-scripts test",
      "eject": "react-scripts eject",
      "build:css": "postcss src/assets/tailwind.css -o src/assets/main.css",
      "watch:css": "postcss src/assets/tailwind.css -o src/assets/main.css"
    }
 * npm start. After this command main.css should be filled automatically   



## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

