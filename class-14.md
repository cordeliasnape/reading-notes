### How would you describe an object to a non-technical friend you grew up with?

An object is some code that allows you to set the values of each property of an item by referring to it using a constructor function. For example:

> function Friend (name, age, job) {
> this.name = name;
> this.age = age;
> this.job = job;
> }
> I could now add information about each of my friends using an object. You define an object by beginning it with ‘new’:

> `new Friend (“Cordelia”, “25”, student);`

This would now set each value of the `Friend`.

### What are some advantages to creating object literals?

It can be much more convenient to use object literals and can allow devs to have more flexibility in declaration and write less code during declaration.

### How do objects differ from arrays?

Arrays are a type of list with accessible data. Objects organise data in a manageable way, allowing for data to be accessed based on its type declared in the object.

### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

let arrayExample = [“a”, “b”, “c”]

In order to access “b” in the console log, I would need to use bracket notation. Dot notation just wouldn’t be useful here.

> `console.log(arrayExample[1]);``

### Evaluate the code below. What does the term this refer to and what is the advantage to using this?

> const dog = {
> name: 'Spot',
> age: 2,
> color: 'white with black spots',
> humanAge: function (){
> console.log(`${this.name} is ${this.age*7} in human years`);
> }
> }

This is just a simple JavaScript object. It’s useful because it’s organised, dynamic (I can update it and remove items, etc) and it allows me to encapsulate data in one item.

### What is the DOM?

The DOM, or Document Object Model is a programming interface that allows the user to access part of the HTML on the page through JavaScript. It allows for the creation of interactive and responsive web apps.

### Briefly describe the relationship between the DOM and JavaScript.

JavaScript is the most common language used to access the DOM, allowing for page interactivity and responsiveness.
