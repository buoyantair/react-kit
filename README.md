<img src="http://i.imgur.com/b5Ole4s.png" height="100" />
---
A minimalistic kit to bootstrap a React application with a set of pre-configured tools.

## Included tools
- [yarn]() a powerful package manager
- [react]() (obviously)
- [redux]() library to manage the data flow
- [webpack](https://webpack.github.io/docs/) as module bundler

### Loaders
- [babel-loader](https://github.com/babel/babel-loader) to use Ecmascript features and transpile JSX
- [sass-loader](https://github.com/jtangelder/sass-loader) to compile sass files
- [ejs-loader](https://github.com/okonet/ejs-loader) to customize the generated `index.html` file

### Others
- [eslint](http://eslint.org/) to get a Javascript linter
- [webpack-dev-server](https://webpack.github.io/docs/webpack-dev-server.html) to get a development server
- [html-webpack-plugin](https://github.com/ampedandwired/html-webpack-plugin) to generate an `index.html` file automatically

## Usage
```
npm install -g yarn
```
Installs the [yarn]() package manager.

```
yarn build
```
Builds your project into the `build/` directory.

```
yarn start
```
Starts a development server running on `http://localhost:8080`.  
**Caution**: do not use this command for production.




