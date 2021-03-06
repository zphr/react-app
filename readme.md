# Lightweight React boilerplate using Webpack 4
> Highly scalable architecture with a production build 4 times smaller than [Create React App](https://github.com/facebook/create-react-app)

## Install
Clone this project and run:
#### `npm install` or `yarn install`

## Getting started

#### 1. `npm start` or `yarn start`

Runs the app in development mode.<br>
Open [http://localhost:9000](http://localhost:9000) to view it in the browser.

The page will automatically modify without reloading when you make changes to the code. (React Hot Loader) <br>
You will see the build errors and lint warnings in the console.

#### 2. `npm run test` or `yarn test`

Runs the test watcher in an interactive mode.<br>
By default, runs tests related to files changed since the last commit.

#### 3. `npm run build` or `yarn build`

Builds the app for production to the `public` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>

Your app is ready to be deployed.

#### 4. `npm run analysis` or `yarn analysis` (Webpack Bundle Analyzer)

This script will help you:
* Realize what's really inside your bundle
* Find out what modules make up the most of it's size
* Find modules that got there by mistake
* Optimize it!
* And the best thing is it supports minified bundles! It parses them to get real size of bundled modules. And it also shows their gzipped sizes!

## Folder Structure

```
├───devtools
│   ├───test                         // Jest and Enzyme config files
│   │   └───mocks
│   └───webpack                      // Webpack config files
└───src
    ├───components                   // Reusable components
    │   └───title
    │       └───test
    │           └───__snapshots__
    ├───gui                          // Layout and theming
    │   ├───layout
    │   └───themes
    │       └───default
    │           ├───fonts
    │           │   └───icons
    │           └───patterns
    ├───libs                         // Custom reusable libraries
    └───modules                      // Complex components that are not reusable even entire pages
        └───app
            └───test
                └───__snapshots__
```

## Base App

| Package       |Version |
| ------------- |--------|
| React         |^16.x.x |
| [xBEM][1]     |^0.x.x  |
| Jest          |^23.x.x |
| Enzyme        |^3.x.x  |
| Babel         |^6.x.x  |
| Webpack       |^4.x.x  |

[1]: https://github.com/bogdan-prisecaru/xbem

## Using

* Scope Hoisting
* Uglification of base app via `webpack --mode production`
* [React Hot Loader](https://github.com/gaearon/react-hot-loader)
* Deterministic Hashes
* [Webpack Bundle Analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer)

## App's Size In Production

* All (36 KB)
* vendor.ae9379741f871b6ba2be.js (34.11 KB)
* index.1f1cbf641d603d86f8ee.js (1.89 KB)

## Thank You

* [Bogdan Prisecaru (@bogdan-prisecaru)](https://github.com/bogdan-prisecaru)

## Feedback and Suggestions
> If you want to leave some suggestions or give me constructive feedback please don't hesitate to open an issue I will gladdly look into into it.

>Thank you for your time! :wink:
