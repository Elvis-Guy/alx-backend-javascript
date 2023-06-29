# ES6 classes

ES6 (ECMAScript 2015) introduced a new syntax for creating classes in JavaScript, known as ES6 classes. Prior to ES6, JavaScript used prototype-based inheritance instead of class-based inheritance. ES6 classes provide a more familiar syntax for developers coming from traditional class-based languages.


### Example of classes in ES6

```javascript

class Rectangle {
  constructor(width, height) {
    this.width = width;
    this.height = height;
  }

  calculateArea() {
    return this.width * this.height;
  }

  static createSquare(side) {
    return new Rectangle(side, side);
  }
}


```


## Learning Objectives

* How to define a Class
* How to add methods to a class
* Why and how to add a static method to a class
* How to extend a class from another
* Metaprogramming and symbols

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
