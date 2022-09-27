# Problem Domain, Objects, and the DOM

[Return to Home](https://sethppierce.github.io/reading-notes)

## Questions

### Why this matters

This matters because using objects for multiple variables that have multiple properties can be accessed through a single variable more easily.
DOM matters because for our webpage to be more dynamic we need to use DOM manipulations to populate or remove new HTML elements.

### JavaScript Object Basics

How would you describe an object to a non-technical friend you grew up with? It's like a social media profile, it shows a name but once you get into the profile it shows more information
What are some advantages to creating object literals? contains more information in one variable
How do objects differ from arrays? Objects represent “things” with properties, while arrays create and store lists of data in a single variable
Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation. when you need to access a property using a variable.
Evaluate the code below. What does the term this refer to and what is the advantage to using this?
object, it stores properties in a singe variable and the main advantage is that we can access information from a single variable with less.

``` javascript
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

### Introduction To The DOM

What is the DOM?  Document Object Model
Briefly describe the relationship between the DOM and JavaScript. javascript uses DOM to create and append HTML Elements to the your HTML page.