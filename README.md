# React Projects 2nd Edition

[React Projects - Second Edition](https://www.packtpub.com/product/react-projects-second-edition/9781801070638)

## Chapter 1 SPA

### Pre-requisites

- Git
- Node 
- NPM

```sh
npm init -y
curl https://raw.githubusercontent.com/github/gitignore/main/Node.gitignore -o .gitignore
# alterative to curl use
# echo "node_modules" > .gitignore
npm i -D webpack webpack-cli
mkdir src && echo "console.log('Rick and Morty')" > src/index.js
# package.json add "start": "webpack --mode development && node dist/main.js",
npm start
```

Add react

```sh
npm i react react-dom
npm i -D @babel/core babel-loader @babel/preset-env @babel/preset-react
# see webpack.config.js
# see babel.config.js
# mkdir public and add an index.html
npm i -D html-webpack-plugin
npm i -D webpack-dev-server
```






