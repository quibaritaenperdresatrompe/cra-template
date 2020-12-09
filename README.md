## Based on Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

n.b. you need to provide required config in the `.env` file

### `test`

Launches the test runner in the interactive watch mode and generate the coverage reports into the terminal and [LCOV format](https://wiki.documentfoundation.org/Development/Lcov) in [`./coverage/lcov-report/` folder](./coverage/lcov-report/). This report is available locally by running the [`coverage`](#coverage) command.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `coverage`

Opens, in browser, the LCOV Code Coverage report.<br />
Open [http://localhost:4004](http://localhost:4004) to view it in the browser.

### `build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

n.b. you need to provide required config in the `.env` file

### `commit`

Runs the [`git-cz`](https://github.com/streamich/git-cz) CLI to generate commit messages according to the [_Conventional Commit specifications_](https://www.conventionalcommits.org/en/v1.0.0/#specification).

### `format`

Prettifies code with [Prettier](https://prettier.io/).

To improve DX we recommended to integrate Prettier in your IDE.
e.g. in Visual Studio code with [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) plugin and following configuration:

```json
{
  "files.autoSave": "onFocusChange",
  "editor.formatOnSave": true
}
```

### `analyze`

Creates a tree-map visualization of bundles size with [`source-map-explorer`](https://www.npmjs.com/package/source-map-explorer).

### `storybook`

Runs the Storybook.<br />
Open [http://localhost:6006](http://localhost:6006) to view it in the browser.<br/>

More informations on https://storybook.js.org/docs/react/api/cli-options#start-storybook.

### `build-storybook`

Builds the Storybook app for production to the `storybook-static` folder.<br/>

More informations on https://storybook.js.org/docs/react/api/cli-options#build-storybook.
