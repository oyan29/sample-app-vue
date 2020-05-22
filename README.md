# sample-app-vue

## Overview
This is a template repository, which would help any level of developers to quickly start to develop a web application using Firebase as a backand and Vue as a front-end.

In addition to Firebase and Vue, we have chosen Vuetify as the UI library.

## Quick Start Guide
Requirements:

* A Google account
* An account on Github
* A development machine (MacOS machine is recommanded)
* A source code editor (Microsoft Visual Studio Code is recommanded)
* npm
* Firebase Tools (run "npm install -g firebase-tools")

Steps:

1. Fork this repository (on github)
1. "git clone" that repository
1. Create your own project in Firebase console, then create a Web App and Firestore and enable Email authentication.
1. Create your own project.ts at src/config directory by copy & paset firbaseConfig from Firebase console, and add export it, wihch should look like this.
1. Create .firebaserc file based on your firebase project name, which looks like this:
1. run "firebase login" to login to your Google account
1. run "npm install" to install required node modules
1. run "npm run serve" to run it locally for development
1. open "http://localhost:8080" on your browser

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
