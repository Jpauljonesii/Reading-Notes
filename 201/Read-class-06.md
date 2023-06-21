# Read: Class 06

## JavaScript Object Basics

This topic matters because objects will help put more details data with javascript and be able to manipulate JavaScript with DOM. 

1. How would you describe an object to a non-technical friend you grew up with? An object is a collection of related data and/or functionality. These usually consist of several variables and functions (which are called properties and methods when they are inside objects).
2. What are some advantages to creating object literals? To transfer a series of structured, related data items in some manner. If you create more than one, this enables you to use the same method definition for every object you create. Sending a single object is much more efficient than sending several items individually, and it is easier to work with than an array, when you want to identify individual items by name.
3. How do objects differ from arrays? Arrays use numbers to access its elements, objects used names to access its members.
4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation. if an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using bracket notation.
5. Evaluate the code below. What does the term this refer to and what is the advantage to using this? The this keyword refers to the current object the code is being written inside. In this example it refers to the dog. this enables you to use the same method definition for every object you create.
const dog = {

  name: 'Spot',

  age: 2,

  color: 'white with black spots',

  humanAge: function (){

    console.log(`${this.name} is ${this.age*7} in human years`);

  }

}

## Introduction To The DOM

1. What is the DOM? The Document Object Model (DOM) is a programming interface for web documents.
2. Briefly describe the relationship between the DOM and JavaScript. The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts.

## Things I want to know more about

I want to know about objects in general and DOM manipulation as I become a more seasoned developer.
