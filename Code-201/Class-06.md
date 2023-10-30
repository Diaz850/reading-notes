# JavaScript Object Basics
### How would you describe an object to a non-technical friend you grew up with?
I would describe it to him as a lunchbox. Where the lunchbox is the object and inside that lunchbox we have all types of properties that we keep organized
in it.
### What are some advantages to creating object literals?
Creating object literals in JavaScript is advantageous because they allow you to organize related data and behavior into a single, easily accessible package.
### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
const myObject = {
  "property with space": "I'm accessed using bracket notation",
  "123property": "I'm also accessed using bracket notation"
};

console.log(myObject["property with space"]); // Outputs: I'm accessed using bracket notation
console.log(myObject["123property"]); // Outputs: I'm also accessed using bracket notation
In this example, using dot notation wouldn't work because of the property names containing spaces and starting with a number. Bracket notation allows you to access these properties correctly.

### Evaluate the code below. What does the term this refer to and what is the advantage to using this?
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

The code defines an object named dog with properties such as name, age, color, and a method named humanAge. In this context:
The term this refers to the current instance of the dog object. It allows the method to access the properties of the object it belongs to.
The advantage of using this is that it allows you to access the object's own properties and methods within its functions or methods. In the humanAge method, this.name and this.age are used to access the name and age properties of the dog object. This makes the code more flexible and reusable because you can create multiple dog objects with different names and ages, and the humanAge method will work correctly for each of them. It avoids hard-coding specific property values and makes the code more maintainable and adaptable.


# Introduction To The DOM

### What is the DOM?
The DOM, or Document Object Model, is a programming interface that represents and allows interaction with the structure and content of a web page, 
making it accessible and manipulable for scripting.

### Briefly describe the relationship between the DOM and JavaScript.
The DOM and JavaScript are like a team. The DOM is like the structure of a building, and JavaScript is like the worker who can change and interact with the building.
JavaScript can move things around, add new stuff, or even make things disappear in that building (the DOM). 
They work together to make websites dynamic and interactive.

Source = ChatGPT and Google


