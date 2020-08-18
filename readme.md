## Setup
- yarn init -y
- yarn add react react-dom
- yarn add @babel/core @babel/preset-env 
- yarn add @babel/preset-react webpack webpack-cli
- yarn add @babel/cli
- yarn add babel-loader
- yarn add webpack-dev-server -D

## Vs Code Snippets/plugins
- html:5
- div#app

## Run babel from cli
- yarn babel src/index.js --out-file public/bundle.js

## Run webpack from cli
- yarn webpack --mode development
- yarn webpack-dev-server --mode development