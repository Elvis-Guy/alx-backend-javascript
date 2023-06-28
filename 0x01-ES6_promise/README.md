# ES6 Promises

Promises are a way to handle asynchronous operations in JavaScript. They represent a value that may be available now or in the future. Promises have three states: pending, fulfilled, or rejected. The Promise constructor takes a function with two arguments, `resolve` and `reject`, which are used to determine the outcome of the Promise.


## Learning Objectives

* Promises (how, why, and what)
* How to use the `then`, `resolve`, `catch` methods
* How to use every method of the Promise object
* Throw / Try
* The await operator
* How to use an `async` function

```
 curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
 sudo bash nodesource_setup.sh
 sudo apt install nodejs -y
 $ nodejs -v
 v12.11.1
 $ npm -v
 6.11.3

```

### Install Jest, Babel, and ESLint


* Install Jest using: `npm install --save-dev jest`
* Install Babel using: `npm install --save-dev babel-jest @babel/core @babel/preset-env`
* Install ESLint using: `npm install --save-dev eslint`
