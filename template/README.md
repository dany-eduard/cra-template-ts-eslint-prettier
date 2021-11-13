# cra-template-ts-eslint-prettier

React template in TypeScript preconfigured with Eslint and Prettier. The base project was created with `create-react-app` using the typescript template using the command [`npx create-react-app my-app --template typescript`](https://create-react-app.dev/docs/adding-typescript/).

## Clone

```zsh
git clone https://github.com/dany-eduard/cra-template-ts-eslint-prettier.git
```

## Eslint Rules

- [`import/extensions`: Ensure consistent use of file extension within the import path](https://github.com/import-js/eslint-plugin-import/blob/main/docs/rules/extensions.md)
- [`import/no-extraneous-dependencies`: Forbid the use of extraneous packages](https://github.com/import-js/eslint-plugin-import/blob/main/docs/rules/no-extraneous-dependencies.md)
- [`react/jsx-filename-extension`: Restrict file extensions that may contain JSX](https://github.com/yannickcr/eslint-plugin-react/blob/master/docs/rules/jsx-filename-extension.md)
- [`react/jsx-props-no-spreading`: Disallow JSX props spreading](https://github.com/yannickcr/eslint-plugin-react/blob/master/docs/rules/jsx-props-no-spreading.md)
- [`react/function-component-definition`: Enforce a specific function type for function components](https://github.com/yannickcr/eslint-plugin-react/blob/master/docs/rules/function-component-definition.md)
- [`no-use-before-define`: Disallow the use of variables before they are defined](https://eslint.org/docs/rules/no-use-before-define)
- [`@typescript-eslint/no-use-before-define`: Disallow the use of variables before they are defined](https://github.com/typescript-eslint/typescript-eslint/blob/master/packages/eslint-plugin/docs/rules/no-use-before-define.md)
- [`react/react-in-jsx-scope`: Prevent missing React when using JSX](https://github.com/yannickcr/eslint-plugin-react/blob/master/docs/rules/react-in-jsx-scope.md)

## Prettier Rules

- [`printWidth`](https://prettier.io/docs/en/options.html#print-width): `120`
- [`semi`](https://prettier.io/docs/en/options.html#semicolons): `false`
- [`singleQuote`](https://prettier.io/docs/en/options.html#quotes): `true`
- [`tabWidth`](https://prettier.io/docs/en/options.html#tab-width): `2`
- [`trailingComma`](https://prettier.io/docs/en/options.html#trailing-commas): `es5`
- [`useTabs`](https://prettier.io/docs/en/options.html#tabs): `false`

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
