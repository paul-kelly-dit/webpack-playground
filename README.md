# webpack-playground

```
npm init -y
```

Created this file

```
{
  "name": "webpack-playground",
  "version": "1.0.0",
  "description": "npm init -y",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/paul-kelly-dit/webpack-playground.git"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/paul-kelly-dit/webpack-playground/issues"
  },
  "homepage": "https://github.com/paul-kelly-dit/webpack-playground#readme"
}
```

Install webpack

```
npm i -D webpack webpack-cli
```

add this following to your scripts 

```
"scripts": {
    "dev": "webpack --mode development",
    "prod": "webpack --mode production"
  }
```

can type

```
npm run dev
```

Install new dependencies
```
npm i -D babel-core babel-preset-env babel-loader
```

babel-core and babel-preset-env to get babel setup ready to transpile ES6+ to ES5. Secondly, babel-loader enables us to use babel with webpack to transpile any .js file.

Next, install 
```
npm i -D html-webpack-plugin
```

add a html file in public dir

```html

```