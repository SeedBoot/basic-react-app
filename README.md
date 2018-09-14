# basic-react-app

I've made this as light as possible, so it's nice and easy to get a new project started.

This repo contains:
```
"dependencies": {
    "react": "^16.5.0",
    "react-dom": "^16.5.0"
},
"devDependencies": {
    "@babel/core": "^7.0.0",
    "@babel/preset-env": "^7.0.0",
    "@babel/preset-react": "^7.0.0",
    "babel-loader": "^8.0.2",
    "css-loader": "^1.0.0",
    "html-loader": "^0.5.5",
    "html-webpack-plugin": "^3.2.0",
    "jest": "^23.6.0",
    "style-loader": "^0.23.0",
    "webpack": "^4.17.2",
    "webpack-cli": "^3.1.0",
    "webpack-dev-server": "^3.1.8"
}
```

scripts include:
 - `"build": "webpack --mode production"`
 - `"watch": "webpack-dev-server --mode development"`
 - `"test": "jest ./src"`
