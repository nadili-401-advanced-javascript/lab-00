# LAB - 00

## Proof of Life Server

### Author: Nadya Ilinskaya/Seattle-js-401n14

### Links and Resources
* [submission PR](https://github.com/nadili-401-advanced-javascript/lab-00/pull/1)
* [travis](https://travis-ci.com/nadili-401-advanced-javascript/lab-00)
* [front-end](https://nadili-lab-00.herokuapp.com/)

#### Documentation
* [jsdoc](https://nadili-lab-00.herokuapp.com/docs/)

### Modules
#### `pos.js`
##### Exported Values and Methods

###### `isAlive(dead) -> boolean`
Returns true/false to indicate how server works

### Setup
#### `.env` requirements
* `PORT` - Port Number

#### Running the app
* `npm start`
* Endpoint: `/`
  * Returns a boolean.
* Endpoint: `/docs`
  * Returns a JSdoc.
  
#### Tests
* Unit Tests: 'npm test'
* Lint Tests: 'npm run lint'

#### UML
![UML Diagram](whiteboard.jpg)
