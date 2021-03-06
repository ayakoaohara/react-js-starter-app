## Concept
This project shows some basic usage of React.js features, including:
- components written as Javascript functions and JSX
- passing arguments (a.k.a props) to components
- maintaing state (i.e. internal data fields) within a component
- fetching data from an API and injecting it into a component
- creating shared global navigation links across all screens
- linking from one component to another
- passing params from one component to another in the URL
- use of a `.gitignore` file to exclude 3rd-party code and autogenerated files from version control tracking
- use of a `package.json` with npm to track dependencies and streamline installation.

Many of the features of React exhibited in this project are explained at a high level in this [prepared lecture presentation](https://nyu-computer-science.github.io/software-engineering/react-intro/).

## Intentional exclusions
There are some common practices that we have not included here, since we believe they are distraction's from a beginner's ability to master React's code patterns.
- use of a state manager, such as Redux or Mobx
- use of a front-end framework, such as Bootstrap or Material Design
- use of a rendering engine, such as Handlebars or Pug
- use of a custom back-end API
- inclusion of user account registration or log in functionality

## Origins
The code here is built on top of the boiler plate code bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm install`

Installs all the dependencies listed in the `package.json` configuration file.
This is necessary before running the app, since the 3rd-party dependency code is excluded from version control by the `.gitignore` git settings file.

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
