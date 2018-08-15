# Tasks

## Q1) Render these into component:
* const name = "Hello World";
* const obj = {name: "Hello World Object"}
* const data = ['We', 'are', 'United'] //Show these in seperate tags
* const list = [{name: "Hello World 1"}, {name: "Hello World 2"}, {name: "Hello World 3"}] //Show these in seperate tags
* const complex = [{company: 'XYZ', jobs: ['Javascript', 'React']}, {company: 'ABC', jobs: ['AngularJs','Ionic']}]

## Answer: 

 * **hosted [here](https://gmt95.github.io/react_assignment_2/)**
 * ***this repo***

## Q2) Briefly explain with an example what's the difference between import Something from 'package' VS import {Something} from 'package'

## Answer:

There are two types of exports:
 * default export
 * named export

In ***default export*** we export like this:
```javascript
export default <class_name>
``` 
and import like this:
```javascript
import <class_name> from './link_of_js_file'
```
and there can be only one *default export* in Javascript,whereas there can be *zero or more* ***named exports*** 

In ***named export*** we *export* like this:
```javascript
export { <class_name>/<function_name> }
``` 
and *import* like this:
```javascript
import { <class_name> } from './link_of_js_file'
```

## Q3) Just copy and paste the data from these links and store them into a variable:
 * const posts = https://jsonplaceholder.typicode.com/posts //copy the array from this link
* const users = https://jsonplaceholder.typicode.com/users //copy the array from this link
//DON'T USE FETCH FOR NOW

Using above API's, you've to render all the users with their names, emails and their posts.
Use \`id` as a key with each data rendering.

## Answer:

 * **hosted [here](https://gmt95.github.io/react_assignment_2/) *see(6) Rendering \`JSON from link` in variable) after opening link*** 
 * ***this repo***

- - - 

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).




