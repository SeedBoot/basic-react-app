# react-seed

### A React seed, ready to be planted!
I've made this as light as possible, so it's nice and easy to get a new project started.

This repo is suitable for Development. It will need additional configuring if it to be used for Prod. For instance, I've now included `extract-css-chunks-webpack-plugin` which pulls all css into one file. But it doesn't have the ability to uglify... yet

### Install
`git clone https://github.com/SeedBoot/react-seed.git`

`npm i`

`npm run watch`

:fire:

### This repo contains:
```javascript
"dependencies": {
    "react": "^16.5.0",
    "react-dom": "^16.5.0"
},
"devDependencies": {
 "@babel/core": "^7.1.2",
    "@babel/preset-env": "^7.1.0",
    "@babel/preset-react": "^7.0.0",
    "babel-loader": "^8.0.4",
    "css-loader": "^1.0.0",
    "extract-css-chunks-webpack-plugin": "^3.1.3",
    "html-loader": "^0.5.5",
    "html-webpack-plugin": "^3.2.0",
    "jest": "^23.6.0",
    "optimize-css-assets-webpack-plugin": "^5.0.1",
    "style-loader": "^0.23.0",
    "uglifyjs-webpack-plugin": "^2.0.1",
    "webpack": "^4.20.2",
    "webpack-cli": "^3.1.2",
    "webpack-dev-server": "^3.1.9"
}
```

### scripts include:
 - `"build": "webpack --mode production"`
 - `"watch": "webpack-dev-server --mode development"`
 - `"test": "jest ./src/**/*.test.js"`

***

## TODO
 - Create Dev and Prod scripts for builds
 - Create example test
