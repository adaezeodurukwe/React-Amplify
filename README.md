# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## To run this app

If you don't have amplify cli installed globally, run
### `npm install -g @aws-amplify/cli`

install packages by running
### `yarn`

in the project directory, initialize amplify
### `amplify init`

To pull down the latest of your project's backend development and also recreate the aws-exports.json file, run 

### `amplify env pull`

The above command may require `sudo` on macbooks

## To start the App
### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
