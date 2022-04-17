# react-scripts for chrome extension

How beautiful is create-react-app, just type the magic command, and you will get pre-structured and pre-configured app for your quick start. But what to do, when you want to develop chrome extension with react. 

### Here is it!!!

Just type the following command in your console and press enter.

```sh
npx create-react-app my-chrome-extension --scripts-version web-extension --template web-extension-typescript
```
After we get a brand new project with the following folder structure,

```
app 
├── src
│   ├── background
│   │   └── index.ts
│   ├── contentScript
│   │   └── index.ts
│   ├── options
│   │   ├── index.tsx
│   │   ├── Options.css
│   │   └── Options.tsx
│   ├── popup
│   │   ├── App.css
│   │   ├── App.tsx
│   │   ├── index.css
│   │   └── index.tsx
│   └──  react-app-env.d.ts
├── public
│   ├── assets
│   │   ├── icon-16.png
│   │   ├── icon-48.png
│   │   ├── icon-128.png
│   ├── manifest.json
│   ├── options.html
│   └── popup.html
├── .gitignore
├── package-lock.json 
├── package.json
└── tsconfig.json
```


This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app).
Please refer to its documentation:

- [Getting Started](https://facebook.github.io/create-react-app/docs/getting-started) – How to create a new app.
- [User Guide](https://facebook.github.io/create-react-app/) – How to develop apps bootstrapped with Create React App.

##### Info: This version corresponding to react-scripts v5.0.1