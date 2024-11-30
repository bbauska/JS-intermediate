JS Intermediate JavaScript
(JS-Int-JavaScript)

Intermediate/advanced material
•	JavaScript Design Patterns 
•	Professor Frisby's Mostly Adequate Guide to Functional Programming 
•	What the heck is the event loop anyway? – JS Conf talk about the event loop
•	Deep JavaScript: Theory & Techniques 
Key Concepts:
•	Objects:
Objects are the fundamental building blocks of JavaScript. They are collections of key-value pairs, where keys are properties (variables) and values can be any data type, including functions (methods).
•	Prototypes:
Every object in JavaScript has a prototype, which is another object from which it inherits properties and methods. This allows for efficient sharing of behavior and data between objects.
•	Constructors:
Constructors are special functions used to create objects with specific properties and methods. They act as blueprints for objects.
•	Classes (ES6):
Introduced in ECMAScript 2015 (ES6), classes provide a more syntactically familiar way to define objects and their behavior. However, under the hood, they still utilize prototypes.

1.	Advanced Data Types and Manipulation:
•	Explore advanced data types like Sets, Maps, and Symbols.
•	Learn how to manipulate arrays and objects using advanced techniques such as destructuring, spreading, and rest parameters.
•	Understand how to use the Array methods like map, filter, reduce, and forEach effectively.

2.	Asynchronous JavaScript:
•	Dive into asynchronous programming concepts like callbacks, promises, and async/await.
•	Learn how to handle asynchronous operations using techniques like chaining promises and error handling.
•	Understand how to make API calls and handle responses asynchronously.

3.	Object-Oriented Programming (OOP):
•	Learn about OOP principles like encapsulation, inheritance, and polymorphism.
•	Explore how to create and use classes, constructors, and prototypes in JavaScript.
•	Understand the concept of "this" and how it behaves in different contexts.

4.	Functional Programming: 
Functional programming in JavaScript is all about treating your code as a set of independent, reusable functions that operate on data without side effects
•	Explore functional programming concepts like higher-order functions, pure functions, and immutability.
•	Learn how to use functional programming techniques like map, filter, and reduce to solve problems.
•	Understand the benefits of functional programming and how it can improve code readability and maintainability.

5.	Error Handling and Debugging:
•	Learn how to handle and throw errors effectively in JavaScript.
•	Explore debugging techniques using browser developer tools and console statements.
•	Understand how to use try-catch blocks to handle exceptions and prevent application crashes.

6.	Modules and Bundlers:
•	Learn how to organize your code into modules for better code organization and reusability.
•	Explore popular module systems like CommonJS and ES modules.
•	Understand how to use bundlers like Webpack or Rollup to bundle and optimize your JavaScript code.

7.	Testing and Test-Driven Development (TDD):
•	Learn how to write unit tests using frameworks like Jest or Mocha.
•	Understand the principles of TDD and how to write tests before implementing functionality.
•	Explore techniques like mocking and stubbing to isolate dependencies during testing.

8.	Browser APIs and DOM Manipulation:
•	Learn how to interact with the Document Object Model (DOM) using JavaScript.
•	Explore browser APIs like Fetch API, Local Storage, and Geolocation.
•	Understand how to manipulate HTML elements, handle events, and create dynamic web applications.

Remember, practice is key to mastering JavaScript. Work on small projects, solve coding challenges, and build real-world applications to solidify your understanding of these concepts. Good luck with your intermediate JavaScript education!
Here are more details on each topic:

1.	Advanced Data Types and Manipulation:
•	Sets: Learn about the Set data structure, which allows you to store unique values of any type.
•	Maps: Explore the Map data structure, which stores key-value pairs and provides efficient lookup and manipulation.
•	Symbols: Understand the Symbol data type, which is used to create unique identifiers.

2.	Asynchronous JavaScript:
•	Callbacks: Learn how to use callbacks to handle asynchronous operations by passing functions as arguments.
•	Promises: Understand the concept of promises, which represent the eventual completion or failure of an asynchronous operation.
•	Async/Await: Explore the async/await syntax, which provides a more readable and synchronous-like way to write asynchronous code.

3.	Object-Oriented Programming (OOP):
•	Encapsulation: Learn how to encapsulate data and behavior within objects using properties and methods.
•	Inheritance: Understand how to create class hierarchies and inherit properties and methods from parent classes.
•	Polymorphism: Explore the concept of polymorphism, which allows objects of different classes to be treated as the same type.

4.	Functional Programming:
•	Higher-Order Functions: Learn how to work with functions as first-class citizens, allowing them to be passed as arguments or returned from other functions.
•	Pure Functions: Understand the concept of pure functions, which always produce the same output for the same input and have no side effects.
•	Immutability: Explore the benefits of immutability, where data cannot be changed once created, leading to more predictable and maintainable code.

5.	Error Handling and Debugging:
•	Throwing Errors: Learn how to throw custom errors using the throw keyword and handle them using try-catch blocks.
•	Debugging Techniques: Explore techniques like console logging, breakpoints, and stepping through code to identify and fix issues.
•	Error Handling Best Practices: Understand how to handle errors gracefully and provide meaningful error messages to users.

6.	Modules and Bundlers:
•	Modules: Learn how to organize your code into separate files and export/import functionality using module systems like CommonJS or ES modules.
•	Bundlers: Understand how bundlers like Webpack or Rollup can bundle your JavaScript modules into a single file, optimizing performance and handling dependencies.

7.	Testing and Test-Driven Development (TDD):
•	Unit Testing: Learn how to write tests for individual units of code to ensure they behave as expected.
•	Test Frameworks: Explore popular test frameworks like Jest or Mocha, which provide utilities for writing and running tests.
•	Mocking and Stubbing: Understand how to create mock objects or stub functions to isolate dependencies and test specific parts of your code.

8.	Browser APIs and DOM Manipulation:
•	DOM Manipulation: Learn how to access and manipulate HTML elements using JavaScript to create dynamic and interactive web pages.
•	Browser APIs: Explore various browser APIs like Fetch API for making HTTP requests, Local Storage for client-side data storage, and Geolocation for retrieving user location.

Remember to practice each topic by building small projects or solving coding challenges. This hands-on experience will help solidify your understanding and improve your skills as an intermediate JavaScript developer.
Certainly! Let's delve deeper into Advanced Data Types and Manipulation in JavaScript, specifically focusing on Sets, Maps, and Symbols. Additionally, I'll provide guidance on how to use GitHub for managing your code and collaborating on projects related to these topics.

1. Advanced Data Types
Sets
•	Definition: A Set is a collection of values where each value must be unique. It can store any type of data (primitive values or object references).
•	Key Methods:
•	new Set(iterable): Creates a new Set. You can initialize it with an array or another iterable.
•	add(value): Adds a new element to the Set.
•	delete(value): Removes an element from the Set.
•	has(value): Checks if a value exists in the Set.
•	clear(): Removes all elements from the Set.
•	size: Returns the number of elements in the Set.
Example:
javascript
const mySet = new Set([1, 2, 3, 4]);
mySet.add(5);
mySet.delete(2);
console.log(mySet.has(3)); // true
console.log(mySet.size); // 4
Maps
•	Definition: A Map is a collection of key-value pairs where keys can be of any type (including objects), and each key must be unique.
•	Key Methods:
•	new Map(iterable): Creates a new Map. You can initialize it with an array of key-value pairs.
•	set(key, value): Adds a new key-value pair to the Map.
•	get(key): Retrieves the value associated with the key.
•	delete(key): Removes the key-value pair from the Map.
•	has(key): Checks if a key exists in the Map.
•	clear(): Removes all key-value pairs from the Map.
•	size: Returns the number of key-value pairs in the Map.
Example:
javascript
const myMap = new Map();
myMap.set('name', 'Alice');
myMap.set('age', 25);
console.log(myMap.get('name')); // Alice
console.log(myMap.size); // 2
Symbols
•	Definition: A Symbol is a unique and immutable primitive value that can be used as an identifier for object properties.
•	Key Characteristics:
•	Symbols are created using the Symbol() function.
•	Each Symbol is unique, even if they have the same description.
•	They are often used to avoid name clashes in object properties.
Example:
javascript
const sym1 = Symbol('description');
const sym2 = Symbol('description');
console.log(sym1 === sym2); // false
const obj = {
  [sym1]: 'value1',
  [sym2]: 'value2'
};
console.log(obj[sym1]); // value1

2. Manipulating Advanced Data Types
•	Using Sets: You can perform operations like union, intersection, and difference by combining Sets.
•	Using Maps: Maps can be used to create dictionaries or associative arrays, allowing for efficient data retrieval.
•	Using Symbols: Symbols can be used to create private properties in objects, enhancing encapsulation.

3. Using GitHub for Code Management
Creating a Repository

1.	Sign in to GitHub: Go to GitHub and sign in or create an account.
2.	Create a New Repository:
•	Click on the "+" icon in the top right corner and select "New repository."
•	Give your repository a name (e.g., advanced-data-types).
•	Optionally, add a description and choose whether it should be public or private.
•	Click "Create repository."
Cloning the Repository
•	Use Git to clone the repository to your local machine:
bash
git clone https://github.com/yourusername/advanced-data-types.git
cd advanced-data-types
Adding Code
•	Create a new JavaScript file (e.g., sets.js, maps.js, symbols.js) and implement examples of Sets, Maps, and Symbols.
•	Use git add to stage your changes:
bash
git add sets.js maps.js symbols.js
Committing Changes
•	Commit your changes with a meaningful message:
bash
git commit -m "Add examples for Sets, Maps, and Symbols"
Pushing to GitHub
•	Push your changes to the remote repository:
bash
git push origin main
Collaborating
•	If you're working with others, you can create branches for new features or fixes:
bash
git checkout -b feature/sets-implementation
•	After making changes, push the branch and create a pull request on GitHub for review.

4. Resources for Learning
•	MDN Web Docs: Comprehensive documentation on Sets, Maps, and Symbols.
•	JavaScript.info: A great resource for in-depth tutorials on advanced JavaScript topics.
By using GitHub to manage your code, you can easily track changes, collaborate with others, and showcase your work. This approach will help you solidify your understanding of advanced data types in JavaScript while also gaining experience with version control and collaboration tools.

5. Asynchronous JavaScript
Asynchronous JavaScript is a programming paradigm that allows JavaScript to perform tasks without blocking the execution of other code. This is particularly important in web development, where you want to maintain a responsive user interface while performing tasks like fetching data from a server or reading files.
To understand asynchronous JavaScript, we can break it down into several sub-problems:

6. Understanding the Event Loop
What is the Event Loop?
•	The event loop is a mechanism that allows JavaScript to perform non-blocking operations by using a single-threaded model.
How does it work?
•	JavaScript executes code in a call stack. When asynchronous operations are initiated (like fetching data), they are sent to the Web APIs (like the browser's networking layer).
•	Once the operation completes, a callback function is placed in the message queue.
•	The event loop continuously checks the call stack and the message queue, executing the callback when the call stack is empty.

7. Callback Functions
What are callbacks?
•	A callback is a function passed as an argument to another function, which is then executed after some operation has been completed.
Example of a callback:
javascript
function fetchData(callback) {
    setTimeout(() => {
        const data = 'Data received';
        callback(data);
    }, 1000);
}

fetchData((data) => {
    console.log(data); // Outputs: Data received
});
3. Promises
What are Promises?
•	A Promise is an object representing the eventual completion (or failure) of an asynchronous operation and its resulting value.
States of a Promise:
•	Pending: The initial state, neither fulfilled nor rejected.
•	Fulfilled: The operation completed successfully.
•	Rejected: The operation failed.
Creating and using a Promise:
javascript
const fetchData = () => {
    return new Promise((resolve, reject) => {
        setTimeout(() => {
            const success = true; // Simulate success or failure
            if (success) {
                resolve('Data received');
            } else {
                reject('Error fetching data');
            }
        }, 1000);
    });
};
fetchData()
    .then(data => console.log(data)) // Outputs: Data received
    .catch(error => console.error(error));
javascript, another example
let myPromise = new Promise((resolve, reject) => {
  setTimeout(() => {
    resolve ('Promise resolved');
  },2000);
});
myPromise.then((result) => {
    console.log(result); // Output after 2 seconds : 'Promise resolved'
});
4. Async/Await
What is Async/Await?
•	Async/Await is a syntactic sugar built on top of Promises that allows you to write asynchronous code in a more synchronous fashion.
How to use Async/Await:
•	You define a function with the async keyword, and within that function, you can use the await keyword to pause execution until the Promise is resolved.
Example:
javascript
const fetchData = () => {
    return new Promise((resolve) => {
        setTimeout(() => {
            resolve('Data received');
        }, 1000);
    });
};
const getData = async () => {
    try {
        const data = await fetchData();
        console.log(data); // Outputs: Data received
    } catch (error) {
        console.error(error);
    }
};
getData();
5. Error Handling
•	Error handling in callbacks:
•	Typically done by passing an error as the first argument to the callback.
•	Error handling in Promises:
•	Use .catch() to handle errors.
•	Error handling with Async/Await:
•	Use try...catch blocks to handle errors.
6. Practical Use Cases
•	Fetching data from APIs:
•	Use fetch() or libraries like Axios to make HTTP requests.
•	Handling user interactions:
•	Use asynchronous code to respond to user actions without blocking the UI.
•	Working with timers and intervals:
•	Use setTimeout and setInterval for delayed or repeated execution.
Conclusion
Asynchronous JavaScript is essential for building responsive web applications. By understanding the event loop, callbacks, promises, async/await, and error handling, you can effectively manage asynchronous operations in your code.
3. Object-Oriented Programming (OOP):
Object-Oriented Programming (OOP) is a programming paradigm that uses "objects" to represent data and methods to manipulate that data. OOP is designed to improve code organization, reusability, and maintainability. To understand OOP, we can break it down into several key concepts and principles:
1. Key Concepts of OOP
a. Objects
•	Definition: An object is an instance of a class that contains properties (attributes) and methods (functions) that define its behavior.
•	Example:
javascript
const car = {
    make: 'Toyota',
    model: 'Corolla',
    year: 2020,
    start: function() {
        console.log('Car started');
    }
};
b. Classes
•	Definition: A class is a blueprint for creating objects. It defines properties and methods that the created objects will have.
•	Example:
javascript
class Car {
    constructor(make, model, year) {
        this.make = make;
        this.model = model;
        this.year = year;
    }

    start() {
        console.log('Car started');
    }
}

const myCar = new Car('Toyota', 'Corolla', 2020);
2. OOP Principles
a. Encapsulation
•	Definition: Encapsulation is the bundling of data (attributes) and methods (functions) that operate on that data within a single unit (class). It restricts direct access to some of an object's components.
•	Example: Using private properties in a class:
javascript
class BankAccount {
    #balance; // Private property
    constructor(initialBalance) {
        this.#balance = initialBalance;
    }
    deposit(amount) {
        this.#balance += amount;
    }
    getBalance() {
        return this.#balance;
    }
}
const account = new BankAccount(100);
account.deposit(50);
console.log(account.getBalance()); // Outputs: 150
b. Inheritance
•	Definition: Inheritance allows a class (child class) to inherit properties and methods from another class (parent class). This promotes code reusability.
•	Example:
javascript
class Vehicle {
  constructor(make, model) {
    this.make = make;
    this.model = model;
  }
  start() {
    console.log('Vehicle started');
  }
}

class Car extends Vehicle {
  constructor(make, model, year) {
    super(make, model); // Call the parent class constructor
    this.year = year;
  }
  honk() {
    console.log('Honk! Honk!');
  }
}

const myCar = new Car('Toyota', 'Corolla', 2020);
myCar.start(); // Outputs: Vehicle started
myCar.honk();  // Outputs: Honk! Honk!
c. Polymorphism
•	Definition: Polymorphism allows methods to do different things based on the object it is acting upon. It can be achieved through method overriding (inherited classes can provide a specific implementation of a method).
•	Example:
javascript
class Animal {
    speak() {
        console.log('Animal speaks');
    }
}

class Dog extends Animal {
    speak() {
        console.log('Woof! Woof!');
    }
}

class Cat extends Animal {
    speak() {
        console.log('Meow!');
    }
}

const myDog = new Dog();
const myCat = new Cat();

myDog.speak(); // Outputs: Woof! Woof!
myCat.speak(); // Outputs: Meow!
d. Abstraction
•	Definition: Abstraction is the concept of hiding the complex implementation details and showing only the essential features of an object. It can be achieved through abstract classes or interfaces.
•	Example:
javascript
class Shape {
  area() {
    throw new Error('Method "area()" must be implemented');
  }
}

class Rectangle extends Shape {
  constructor(width, height) {
    super();
    this.width = width;
    this.height = height;
  }
  area() {
    return this.width * this.height;
  }
}
const myRectangle = new Rectangle(5, 10);
console.log(myRectangle.area()); // Outputs: 50
3. Benefits of OOP
•	Modularity: Code is organized into classes and objects, making it easier to manage.
•	Reusability: Classes can be reused across different parts of an application or in different projects.
•	Maintainability: Changes to a class can be made without affecting other parts of the code.
•	Flexibility: OOP allows for the creation of more flexible and adaptable code through inheritance and polymorphism.
4. Practical Use Cases
•	Game Development: OOP is widely used in game development to represent entities like players, enemies, and items.
•	Web Development: Frameworks like React and Angular use OOP principles to create reusable components.
•	Software Engineering: OOP is used in designing complex software systems, making them easier to understand and maintain.
Conclusion
Object-Oriented Programming is a powerful paradigm that helps in organizing code, promoting reusability, and enhancing maintainability. By understanding the key concepts and principles of OOP, developers can create robust and scalable applications.
4.Functional Programming:
Introduction
Functional programming is a powerful paradigm that has gained significant popularity in recent years, and it's a valuable approach to writing clean, maintainable, and bug-free code in JavaScript.
In this article, we will explore the core concepts of functional programming and provide practical JavaScript examples to help you grasp these concepts more effectively.
Understanding Functional Programming
Imagine your JavaScript code as a series of cooking instructions. In the traditional, imperative approach, you might follow a recipe step by step, using various ingredients, tools, and changing the state of the dish as you go. This is similar to how procedural code works.
Functional programming, on the other hand, is more like cooking with functional ingredients. Each function takes some ingredients and transforms them into a new dish without altering the original ingredients. This immutability is a fundamental concept in functional programming.
First-Class Functions and Higher-Order Functions
In JavaScript, functions are first-class citizens, which means they can be assigned to variables, passed as arguments, and returned from other functions. This is a crucial concept in functional programming. Consider this analogy:
// Function as a first-class citizen
const square = (x) => x * x;
const add = (a, b) => a + b;
const mathOperation = square;

console.log(mathOperation(5)); // Output: 25
Here, mathOperation is a variable that holds a reference to the square function. It's like storing a cooking recipe for later use.
Higher-order functions are functions that operate on other functions, either by taking them as arguments or returning them as results. This is akin to having a recipe that asks for another recipe.
// Function as a first-class citizen
const square = (x) => x * x;
const add = (a, b) => a + b;
const mathOperation = square;

console.log(mathOperation(5)); // Output: 25
In this example, the calculate function takes an operation (a function) and two arguments. It's like creating a new dish by following the instructions of another recipe.
Immutability and Pure Functions
In functional programming, immutability is key. Think of your data as an unchangeable ingredient, and functions as your cooking instructions. Avoid modifying the original data; instead, create new data structures with the changes.
// Immutability
const originalArray = [1, 2, 3];
const newArray = originalArray.map((item) => item * 2);

console.log(newArray); // Output: [2, 4, 6]
console.log(originalArray); // Output: [1, 2, 3]
Pure functions are functions that always return the same output for the same input and have no side effects. They're like well-defined recipes that don't vary their outcome based on the chef's mood or external factors.
// Pure function
const double = (x) => x * 2;
console.log(double(3)); // Output: 6
console.log(double(3)); // Output: 6
Map, Filter, and Reduce
Map, filter, and reduce are fundamental array methods in JavaScript that can greatly simplify your code and are core tools in functional programming.
Imagine an array as a collection of ingredients. Mapping is like transforming each ingredient into something else and creating a new collection. Filtering is like picking specific ingredients that meet your criteria, and reducing is like mixing all the ingredients to create a final dish.
// Using map, filter, and reduce
const ingredients = [1, 2, 3, 4, 5];
const transformedIngredients = ingredients.map((item) => item * 2);
const filteredIngredients = ingredients.filter((item) => item % 2 === 0);
const reducedIngredients = ingredients.reduce((acc, item) => acc + item, 0);
console.log(transformedIngredients); // Output: [2, 4, 6, 8, 10]
console.log(filteredIngredients); // Output: [2, 4]
console.log(reducedIngredients); // Output: 15
Conclusion
Functional programming in JavaScript is all about treating your code as a set of independent, reusable functions that operate on data without side effects. By understanding first-class functions, higher-order functions, immutability, pure functions, and using tools like map, filter, and reduce, you can write more readable, maintainable, and bug-free code.
Just like a skilled chef, functional programmers use the right ingredients and techniques to create exquisite dishes. So, next time you write JavaScript code, think of it as crafting a gourmet meal with functional ingredients – your code will be not only delicious but also easy to maintain and extend.
Functional programming is a paradigm of building computer programs using expressions and functions without mutating state and data.
By respecting these restrictions, functional programming aims to write code that is clearer to understand and more bug resistant. This is achieved by avoiding using flow-control statements (for, while, break, continue, goto) which make the code harder to follow. Also, functional programming requires us to write pure, deterministic functions which are less likely to be buggy.
In this article, we will talk about doing functional programming using JavaScript. We will also explore various JavaScript methods and features that make it possible. In the end, we will explore different concepts associated with functional programming and see why they are so powerful.
Before getting into functional programming, though, one needs to understand the difference between pure and impure functions.
Pure vs. Impure Functions
Pure functions take some input and give a fixed output. Also, they cause no side effects in the outside world.
const add = (a, b) => a + b;
Here, add is a pure function. This is because, for a fixed value of a and b, the output will always be the same.
const SECRET = 42;  
const getId = (a) => SECRET * a;
getId is not a pure function. The reason being that it uses the global variable SECRET for computing the output. If SECRET were to change, the getId function will return a different value for the same input. Thus, it is not a pure function.
let id_count = 0;
const getId = () => ++id_count;
This is also an impure function, and that too for a couple of reasons—(1) it uses a non-local variable for computing its output, and (2) it creates a side effect in the outside world by modifying a variable in that world.
 
This can be troublesome if we had to debug this code.
What’s the current value of id_count? Which other functions are modifying id_count? Are there other functions relying on id_count?
Because of these reasons, we only use pure functions in functional programming.
Another benefit of pure functions is that they can be parallelized and memoized. Have a look at the previous two functions. It’s impossible to parallelize or memoize them. This helps in creating performant code.
The Tenets of Functional Programming
So far, we have learned that functional programming is dependent on a few rules. They are as follows.
1.	Don’t mutate data
2.	Use pure functions: fixed output for fixed inputs, and no side effects
3.	Use expressions and declarations
When we satisfy these conditions, we can say our code is functional.
Functional Programming in JavaScript
JavaScript already has some functions that enable functional programming. Example: String.prototype.slice, Array.protoype.filter, Array.prototype.join.
On the other hand, Array.prototype.forEach, Array.prototype.push are impure functions.
One can argue that Array.prototype.forEach is not an impure function by design but think about it—it’s not possible to do anything with it except mutating non-local data or doing side effects. Thus, it’s okay to put it in the category of impure functions.
Also, JavaScript has a const declaration, which is perfect for functional programming since we won’t be mutating any data.
Pure Functions in JavaScript
Let’s look at some of the pure functions (methods) given by JavaScript.
Filter
As the name suggests, this filters the array.
array.filter(condition);
The condition here is a function that gets each item of the array, and it should decide whether to keep the item or not and return the truthy boolean value for that.
const filterEven = x => x%2 === 0;  
[1, 2, 3].filter(filterEven);  
// [2]
Notice that filterEven is a pure function. If it had been impure, then it would have made the entire filter call impure.
Map
map maps each item of array to a function and creates a new array based on the return values of the function calls.
array.map(mapper)
mapper is a function that takes an item of an array as input and returns the output.
const double = x => 2 * x;  
[1, 2, 3].map(double);  
// [2, 4, 6]
Reduce
reduce reduces the array to a single value.
array.reduce(reducer);
reducer is a function that takes the accumulated value and the next item in the array and returns the new value. It is called like this for all values in the array, one after another.
const sum = (accumulatedSum, arrayItem) => accumulatedSum + arrayItem  
[1, 2, 3].reduce(sum);
// 6
 
Concat
concat adds new items to an existing array to create a new array. It’s different from push() in the sense that push() mutates data, which makes it impure.
[1, 2].concat([3, 4])  
// [1, 2, 3, 4]
You can also do the same using the spread operator.
[1, 2, ...[3, 4]]
Object.assign
Object.assign copies values from the provided object to a new object. Since functional programming is predicated on immutable data, we use it to make new objects based on existing objects.
const obj = {a : 2};  
const newObj = Object.assign({}, obj);  
newObj.a = 3;  
obj.a;  
// 2
With the advent of ES6, this can also be done using the spread operator.
const newObj = {...obj};
Creating Your Own Pure Function
We can create our pure function as well. Let’s do one for duplicating a string n number of times.
const duplicate = (str, n) =>  
	n < 1 ? '' : str + duplicate(str, n-1);
This function duplicates a string n times and returns a new string.
duplicate('hooray!', 3)  
// hooray!hooray!hooray!
Higher-order Functions
Higher-order functions are functions that accept a function as an argument and return a function. Often, they are used to add to the functionality of a function.
const withLog = (fn) => {  
	return (...args) => {  
		console.log(`calling ${fn.name}`);  
		return fn(...args);  
	};  
};
In the above example, we create a withLog higher-order function that takes a function and returns a function that logs a message before the wrapped function runs.
const add = (a, b) => a + b;  
const addWithLogging = withLog(add);  
addWithLogging(3, 4);  
// calling add  
// 7
withLog HOF can be used with other functions as well and it works without any conflicts or writing extra code. This is the beauty of a HOF.
const addWithLogging = withLog(add);  
const hype = s => s + '!!!';  
const hypeWithLogging = withLog(hype);  
hypeWithLogging('Sale');  
// calling hype  
// Sale!!!
One can also call it without defining a combining function.
withLog(hype)('Sale'); 
// calling hype  
// Sale!!!
Currying
Currying means breaking down a function that takes multiple arguments into one or multiple levels of higher-order functions.
Let’s take the add function.
const add = (a, b) => a + b;
When we are to curry it, we rewrite it distributing arguments into multiple levels as follows.
const add = a => {
	return b => {
		return a + b;
	};
};
add(3)(4);  
// 7
The benefit of currying is memoization. We can now memoize certain arguments in a function call so that they can be reused later without duplication and re-computation.
// assume getOffsetNumer() call is expensive
const addOffset = add(getOffsetNumber());
addOffset(4);
// 4 + getOffsetNumber()
addOffset(6);
This is certainly better than using both arguments everywhere.
// (X) DON"T DO THIS  
add(4, getOffsetNumber());  
add(6, getOffsetNumber());  
add(10, getOffsetNumber());
We can also reformat our curried function to look succinct. This is because each level of the currying function call is a single line return statement. Therefore, we can use arrow functions in ES6 to refactor it as follows.
const add = a => b => a + b;
Composition
In mathematics, composition is defined as passing the output of one function into input of another so as to create a combined output. The same is possible in functional programming since we are using pure functions.
To show an example, let’s create some functions.
The first function is range, which takes a starting number a and an ending number b and creates an array consisting of numbers from a to b.
const range = (a, b) => a > b ? [] : [a, ...range(a+1, b)];
Then we have a function multiply that takes an array and multiplies all the numbers in it.
const multiply = arr => arr.reduce((p, a) => p * a);
We will use these functions together to calculate factorial.
const factorial = n => multiply(range(1, n));
factorial(5);
// 120
factorial(6);
// 720
The above function for calculating factorial is similar to f(x) = g(h(x)), thus demonstrating the composition property.
5.Error Handling and Debugging:
Error handling and debugging are crucial aspects of JavaScript development that help identify and resolve issues in the code. Proper error handling ensures that unexpected errors are caught and gracefully handled, while effective debugging techniques help developers find and fix bugs during the development process.
When any error occurs, JavaScript will stop and generate an error message. The throw statement lets you create your own custom error. Technically you can throw your custom exception (throw an error). The exception can be a JavaScript Number, String, Boolean, or Object.
Debugging Techniques in Programming:
1.	Breakpoints: By setting breakpoints in the code, you can pause the program at specific points, check variables, and closely examine the program's current state. ...
2.	Step Through: Examining the code line by line aids in identifying the precise location of an error. ...
3.	Watch Variables:
There are three main types of errors that can occur while compiling a JavaScript program: syntax errors, runtime errors, and logical errors. The most common type of errors are syntax errors, in which something incorrect in the syntax of the program body raises this error.
One of the simplest ways to debug JavaScript code is by using console. log() statements to output variable values or messages to the console. This can help you identify the point at which your code starts to break down or behave unexpectedly. console.
Expert developers expect the unexpected. If something can go wrong, it will go wrong — typically, the moment the first user accesses your new web system.
We can avoid some web application errors like so:
•	A good editor or linter can catch syntax errors.
•	Good validation can catch user input errors.
•	Robust test processes can spot logic errors.
Yet errors remain. Browsers may fail or not support an API we’re using. Servers can fail or take too long to respond. Network connectivity can fail or become unreliable. Issues may be temporary, but we can’t code our way around such problems. However, we can anticipate problems, take remedial actions, and make our application more resilient.
Showing an Error Message is the Last Resort
Ideally, users should never see error messages.
We may be able to ignore minor issues, such as a decorative image failing to load. We could address more serious problems such as Ajax data-save failures by storing data locally and uploading later. An error only becomes necessary when the user is at risk of losing data — presuming they can do something about it.
It’s therefore necessary to catch errors as they occur and determine the best action. Raising and catching errors in a JavaScript application can be daunting at first, but it’s possibly easier than you expect.
How JavaScript Processes Errors
When a JavaScript statement results in an error, it’s said to throw an exception. JavaScript creates and throws an Error object describing the error. We can see this in action in this CodePen demo. If we set the decimal places to a negative number, we’ll see an error message in the console at the bottom. (Note that we’re not embedding the CodePens in this tutorial, because you need to be able to see the console output for them to make sense.)
The result won’t update, and we’ll see a RangeError message in the console. The following function throws the error when dp is negative:
// Division calculation
function divide(v1, v2, dp) {
  return (v1 / v2).toFixed(dp);
}
After throwing the error, the JavaScript interpreter checks for exception handling code. None is present in the divide() function, so it checks the calling function:
// Show result of division
function showResult() {
  result.value = divide(
    parseFloat(num1.value),
    parseFloat(num2.value),
    parseFloat(dp.value)
  );
}
The interpreter repeats the process for every function on the call stack until one of these things happens:
•	it finds an exception handler
•	it reaches the top level of code (which causes the program to terminate and show an error in the console, as demonstrated in the CodePen example above)
Catching Exceptions
We can add an exception handler to the divide() function with a try…catch block:
// Division calculation
function divide(v1, v2, dp) {
  try {
    return (v1 / v2).toFixed(dp);
  }
  catch(e) {
    console.log(`
      error name   : ${ e.name }
      error message: ${ e.message }
    `);
    return 'ERROR';
  }
}
This executes the code in the try {} block but, when an exception occurs, the catch {} block executes and receives the thrown error object. As before, try setting the decimal places to a negative number in this CodePen demo.
The result now shows ERROR. The console shows the error name and message, but this is output by the console.log statement and doesn’t terminate the program.
Note: this demonstration of a try...catch block is overkill for a basic function such as divide(). It’s simpler to ensure dp is zero or higher, as we’ll see below.
We can define an optional finally {} block if we require code to run when either the try or catch code executes:
function divide(v1, v2, dp) {
  try {
    return (v1 / v2).toFixed(dp);
  }
  catch(e) {
    return 'ERROR';
  }
  finally {
    console.log('done');
  }
}
The console outputs "done", whether the calculation succeeds or raises an error. A finally block typically executes actions which we’d otherwise need to repeat in both the try and the catch block — such as cancelling an API call or closing a database connection.
A try block requires either a catch block, a finally block, or both. Note that, when a finally block contains a return statement, that value becomes the return value for the whole function; other return statements in try or catch blocks are ignored.
Nested Exception Handlers
What happens if we add an exception handler to the calling showResult() function?
// Show result of division
function showResult() {

  try {
    result.value = divide(
      parseFloat(num1.value),
      parseFloat(num2.value),
      parseFloat(dp.value)
    );
  }
  catch(e) {
    result.value = 'FAIL!';
  }

}
The answer is … nothing! This catch block is never reached, because the catch block in the divide() function handles the error.
However, we could programmatically throw a new Error object in divide() and optionally pass the original error in a cause property of the second argument:
function divide(v1, v2, dp) {
  try {
    return (v1 / v2).toFixed(dp);
  }
  catch(e) {
    throw new Error('ERROR', { cause: e });
  }
}
This will trigger the catch block in the calling function:
// Show result of division
function showResult() {
  try {
    //...
  }
  catch(e) {
    console.log( e.message ); // ERROR
    console.log( e.cause.name ); // RangeError
    result.value = 'FAIL!';
  }
}
Standard JavaScript Error Types
When an exception occurs, JavaScript creates and throws an object describing the error using one of the following types.
SyntaxError
An error thrown by syntactically invalid code such as a missing bracket:
if condition) { // SyntaxError
  console.log('condition is true');
}
Note: languages such as C++ and Java report syntax errors during compilation. JavaScript is an interpreted language, so syntax errors aren’t identified until the code runs. Any good code editor or linter can spot syntax errors before we attempt to run code.
ReferenceError
An error thrown when accessing a non-existent variable:
function inc() {
  value++; // ReferenceError
}
Again, good code editors and linters can spot these issues.
TypeError
An error thrown when a value isn’t of an expected type, such as calling a non-existent object method:
const obj = {};
obj.missingMethod(); // TypeError
RangeError
An error thrown when a value isn’t in the set or range of allowed values. The toFixed() method used above generates this error, because it expects a value typically between 0 and 100:
const n = 123.456;
console.log( n.toFixed(-1) ); // RangeError
URIError
An error thrown by URI-handling functions such as encodeURI() and decodeURI() when they encounter malformed URIs:
const u = decodeURIComponent('%'); // URIError
EvalError
An error thrown when passing a string containing invalid JavaScript code to the eval() function:
eval('console.logg x;'); // EvalError
Note: please don’t use eval()! Executing arbitrary code contained in a string possibly constructed from user input is far too dangerous!
AggregateError
An error thrown when several errors are wrapped in a single error. This is typically raised when calling an operation such as Promise.all(), which returns results from any number of promises.
InternalError
A non-standard (Firefox only) error thrown when an error occurs internally in the JavaScript engine. It’s typically the result of something taking too much memory, such as a large array or “too much recursion”.
Error
Finally, there is a generic Error object which is most often used when implementing our own exceptions … which we’ll cover next.
Throwing Our Own Exceptions
We can throw our own exceptions when an error occurs — or should occur. For example:
•	our function isn’t passed valid parameters
•	an Ajax request fails to return expected data
•	a DOM update fails because a node doesn’t exist
The throw statement actually accepts any value or object. For example:
throw 'A simple error string';
throw 42;
throw true;
throw { message: 'An error', name: 'MyError' };
Exceptions are thrown to every function on the call stack until they’re intercepted by an exception (catch) handler. More practically, however, we’ll want to create and throw an Error object so they act identically to standard errors thrown by JavaScript.
We can create a generic Error object by passing an optional message to the constructor:
throw new Error('An error has occurred');
We can also use Error like a function without new. It returns an Error object identical to that above:
throw Error('An error has occurred');
We can optionally pass a filename and a line number as the second and third parameters:
throw new Error('An error has occurred', 'script.js', 99);
This is rarely necessary, since they default to the file and line where we threw the Error object. (They’re also difficult to maintain as our files change!)
We can define generic Error objects, but we should use a standard Error type when possible. For example:
throw new RangeError('Decimal places must be 0 or greater');
All Error objects have the following properties, which we can examine in a catch block:
•	.name: the name of the Error type — such as Error or RangeError
•	.message: the error message
The following non-standard properties are also supported in Firefox:
•	.fileName: the file where the error occurred
•	.lineNumber: the line number where the error occurred
•	.columnNumber: the column number on the line where the error occurred
•	.stack: a stack trace listing the function calls made before the error occurred
We can change the divide() function to throw a RangeError when the number of decimal places isn’t a number, is less than zero, or is greater than eight:
// Division calculation
function divide(v1, v2, dp) {

  if (isNaN(dp) || dp < 0 || dp > 8) {
    throw new RangeError('Decimal places must be between 0 and 8');
  }
  return (v1 / v2).toFixed(dp);
}
Similarly, we could throw an Error or TypeError when the dividend value isn’t a number to prevent NaN results:
  if (isNaN(v1)) {
    throw new TypeError('Dividend must be a number');
  }
We can also cater for divisors that are non-numeric or zero. JavaScript returns Infinity when dividing by zero, but that could confuse users. Rather than raising a generic Error, we could create a custom DivByZeroError error type:
// New DivByZeroError Error type
class DivByZeroError extends Error {
  constructor(message) {
    super(message);
    this.name = 'DivByZeroError';
  }
}
Then throw it in the same way:
if (isNaN(v2) || !v2) {
  throw new DivByZeroError('Divisor must be a non-zero number');
}
Now add a try...catch block to the calling showResult() function. It can receive any Error type and react accordingly — in this case, showing the error message:
// Show result of division
function showResult() {

  try {
    result.value = divide(
      parseFloat(num1.value),
      parseFloat(num2.value),
      parseFloat(dp.value)
    );
    errmsg.textContent = '';
  }
  catch (e) {
    result.value = 'ERROR';
    errmsg.textContent = e.message;
    console.log( e.name );
  }

}
Try entering invalid non-numeric, zero, and negative values into this CodePen demo.
The final version of the divide() function checks all the input values and throws an appropriate Error when necessary:
// Division calculation
function divide(v1, v2, dp) {

  if (isNaN(v1)) {
    throw new TypeError('Dividend must be a number');
  }

  if (isNaN(v2) || !v2) {
    throw new DivByZeroError('Divisor must be a non-zero number');
  }

  if (isNaN(dp) || dp < 0 || dp > 8) {
    throw new RangeError('Decimal places must be between 0 and 8');
  }

  return (v1 / v2).toFixed(dp);
}
It’s no longer necessary to place a try...catch block around the final return, since it should never generate an error. If one did occur, JavaScript would generate its own error and have it handled by the catch block in showResult().
Asynchronous Function Errors
We can’t catch exceptions thrown by callback-based asynchronous functions, because an error is thrown after the try...catch block completes execution. This code looks correct, but the catch block will never execute and the console displays an Uncaught Error message after one second:
function asyncError(delay = 1000) {

  setTimeout(() => {
    throw new Error('I am never caught!');
  }, delay);

}

try {
  asyncError();
}
catch(e) {
  console.error('This will never run');
}
The convention presumed in most frameworks and server runtimes such as Node.js is to return an error as the first parameter to a callback function. That won’t raise an exception, although we could manually throw an Error if necessary:
function asyncError(delay = 1000, callback) {
  setTimeout(() => {
    callback('This is an error message');
  }, delay);
}
asyncError(1000, e => {
  if (e) {
    throw new Error(`error: ${ e }`);
  }
});
Promise-based Errors
Callbacks can become unwieldy, so it’s preferable to use promises when writing asynchronous code. When an error occurs, the promise’s reject() method can return a new Error object or any other value:
function wait(delay = 1000) {
  return new Promise((resolve, reject) => {
    if (isNaN(delay) || delay > 0) {
      reject( new TypeError('Invalid delay') );
    }
    else {
      setTimeout(() => {
        resolve(`waited ${ delay } ms`);
      }, delay);
    }
  })
}
Note: functions must be either 100% synchronous or 100% asynchronous. This is why it’s necessary to check the delay value inside the returned promise. If we checked the delay value and threw an error before returning the promise, the function would become synchronous when an error occurred.
The Promise.catch() method executes when passing an invalid delay parameter and it receives to the returned Error object:
// Invalid delay value passed
wait('INVALID')
  .then( res => console.log( res ))
  .catch( e => console.error( e.message ) )
  .finally( () => console.log('complete') );
Personally, I find promise chains a little difficult to read. Fortunately, we can use await to call any function which returns a promise. This must occur inside an async function, but we can capture errors using a standard try...catch block.
The following (immediately invoked) async function is functionally identical to the promise chain above:
(async () => {
  try {
    console.log( await wait('INVALID') );
  }
  catch (e) {
    console.error( e.message );
  }
  finally {
    console.log('complete');
  }
})();
Exceptional Exception Handling
Throwing Error objects and handling exceptions is easy in JavaScript:
try {
  throw new Error('I am an error!');
}
catch (e) {
  console.log(`error ${ e.message }`)
}
Building a resilient application that reacts appropriately to errors and makes life easy for users is more challenging. Always expect the unexpected.
Further information:
•	MDN Control Flow and Error Handling
•	MDN try…catch
•	MDN Error object
Frequently Asked Questions (FAQs) on JavaScript Error Handling
What are the different types of errors in JavaScript?
JavaScript has three types of errors: Syntax Errors, Runtime Errors, and Logical Errors. Syntax Errors occur when there is an issue with the structure of your code, such as a missing bracket or semicolon. Runtime Errors happen when the code is syntactically correct but fails to execute due to unforeseen circumstances like referencing an undefined variable. Logical Errors are the most challenging to debug as they occur when the code runs without crashing, but it doesn’t produce the expected outcome.
How can I handle errors in JavaScript?
JavaScript provides several mechanisms for error handling, including try-catch-finally blocks, throwing exceptions, and using error events. The try-catch-finally block is the most common method. It allows you to “try” a block of code and “catch” any errors that occur. The “finally” block will execute regardless of whether an error was thrown.
What is the purpose of the ‘throw’ statement in JavaScript?
The ‘throw’ statement allows you to create custom error messages in JavaScript. It’s useful when you want to generate an error that the JavaScript engine wouldn’t typically produce. For example, you might want to throw an error if a function argument is not of the expected type.
How can I create a custom error in JavaScript?
You can create a custom error in JavaScript by defining a new object that inherits from the Error constructor. This new object can then be thrown using the ‘throw’ statement. This is useful when you want to provide more specific error information than the standard Error types provide.
What is the difference between ‘null’ and ‘undefined’ in JavaScript?
In JavaScript, ‘null’ and ‘undefined’ both represent the absence of value. However, they are used in slightly different contexts. ‘Undefined’ means a variable has been declared but has not yet been assigned a value. On the other hand, ‘null’ is an assignment value that represents no value or no object.
How can I debug JavaScript errors?
Debugging JavaScript errors can be done using various tools and techniques. Most modern browsers come with built-in developer tools that include a JavaScript console, which displays errors and allows you to interact with your code. You can also use breakpoints to pause code execution and inspect the current state.
What is ‘strict mode’ in JavaScript and how does it help with error handling?
Strict mode’ is a feature in JavaScript that helps catch common coding mistakes and “unsafe” actions. For example, in strict mode, variables must be declared with ‘var’, ‘let’, or ‘const’. Trying to use an undeclared variable will result in an error. This can help prevent bugs that are difficult to detect.
What is the difference between a ‘TypeError’ and a ‘ReferenceError’ in JavaScript?
A ‘TypeError’ occurs when an operation could not be performed, typically when a value is not of the expected type. A ‘ReferenceError’ is thrown when trying to dereference a variable that has not been declared.
How can I handle asynchronous errors in JavaScript?
Asynchronous errors can be handled using promises or async/await. Promises have ‘catch’ and ‘finally’ methods similar to try-catch-finally blocks. With async/await, you can use a try-catch block to handle errors in asynchronous code.
What is the ‘onerror’ event handler in JavaScript?
The ‘onerror’ event handler is a global event handler in JavaScript that catches errors that occur in the window context. It can be used to log uncaught exceptions or to handle them in a custom way.
Throwing Error objects and handling exceptions is easy in JavaScript:
try {
  throw new Error('I am an error!');
}
catch (e) {
  console.log(`error ${ e.message }`)
}
6. Modules and Bundlers:
In JavaScript, modules and bundlers play a crucial role in organizing and optimizing code for modern web development. Here's a breakdown:
Modules:
•	What they are:
Modules are self-contained units of code that encapsulate functionality. They allow you to break down your code into smaller, manageable pieces, making it easier to maintain and reuse.
•	Benefits:
•	Organization: Modules help you organize your code by separating concerns into logical units.
•	Reusability: You can easily reuse modules across different parts of your application or even in other projects.
•	Encapsulation: Modules hide their internal implementation details, exposing only what's necessary.
•	Syntax:
JavaScript supports two main module formats:
•	CommonJS: Used primarily in Node.js, it uses require to import modules and module.exports to export them.
•	ES Modules: The standard module format in modern JavaScript, it uses import and export statements.
Example (ES Modules):
JavaScript
// module1.js
export function greet(name) {
  console.log(`Hello, ${name}!`);
}
// app.js
import { greet } from './module1.js';
greet('World');
Bundlers:
•	What they are:
Bundlers are tools that take multiple JavaScript modules and combine them into a single file (or a few files) that can be efficiently loaded by a browser.
•	Benefits:
•	Reduced network requests: Browsers have limitations on the number of simultaneous requests they can make. Bundling reduces the number of files to be fetched, improving performance.
•	Dependency management: Bundlers automatically resolve dependencies between modules, ensuring that all required code is included in the final bundle.
•	Code transformations: Bundlers can perform transformations like transpiling (e.g., Babel for converting modern JavaScript to older versions) and minification (reducing file size).
•	Popular Bundlers:
•	Webpack: A powerful and flexible bundler with a wide range of features and plugins.
•	Rollup: A fast and efficient bundler focused on producing small, optimized bundles.
•	Parcel: A zero-configuration bundler that aims to be simple and easy to use.
•	Vite: A fast development server and build tool that leverages native ES modules for lightning-fast development. 
What are Module Bundlers used for?
Module bundlers are used for several other purposes, including:
•	Transpiling, minifying, and optimizing code to improve performance.
•	Resolving naming conflicts and removing unused code via tree shaking.
•	Enabling the use of new JavaScript features, even if the targeted browser does not yet support them.
•	Providing a development environment with features such as live reloading and hot module replacement for faster development iterations.
•	Supporting the use of modern JavaScript features such as ES modules and JSX.
•	Enabling the creation of libraries and frameworks that can be easily distributed and used in other projects.
Popular Module Bundlers
Webpack
Webpack is one of the most popular module bundlers in the JavaScript community. It's highly configurable and can handle a wide variety of use cases. Additionally, it has a large community and a wide range of plugins available.
•	Pros: Highly configurable, a wide range of plugins available, large community.
•	Cons: May be difficult to set up and configure and can produce large bundle sizes.
Esbuild
Esbuild is a relatively new module bundler that aims to provide a very fast and efficient bundling. It's written in Go and focuses on providing great performance, even for large projects. It has a plugin system and can be used with other tools like Rollup.
•	Pros: It's very fast, efficient, and lightweight.
•	Cons: Relatively new and not as widely adopted as other options.
Rollup
Rollup is particularly well-suited for library development. It produces smaller bundle sizes than some other bundlers, which can be beneficial for libraries that are intended to be distributed widely. Additionally, Rollup has a plugin-based architecture that allows for a high degree of customization.
•	Pros: Well-suited for library development, produces smaller bundle sizes.
•	Cons: May not be as well-suited for large, complex projects.
Parcel
Parcel is a relatively new module bundler that aims to provide a simple and easy-to-use experience. It has a minimal configuration and can handle most common use cases out of the box. Moreover, Parcel has a built-in development server, which can be useful for testing and debugging.
•	Pros: Minimal configuration, built-in development server.
•	Cons: May fall short for some advanced use cases.
Vite
Vite is a lightweight module bundler that is designed for development speed. It uses native ES modules in the browser and has a hot module replacement feature that allows for fast development iterations.
•	Pros: It's lightweight, has fast development iterations, and it's easy to set up.
•	Cons: Limited in older browser support, and needs more community traction to become sustainable.
Setting up a Module Bundler
We'll use Webpack as an example, to show you how to set up a module bundler for a simple project:
1.	First, install Webpack and the necessary loaders and plugins by running the following command:
npm install webpack webpack-cli --save-dev
2.	Next, create a webpack.config.js file in the root of your project. This file will contain the configuration for Webpack. The example below contains a configuration file that tells Webpack to use the babel-loader to transpile JavaScript files:
const path = require('path');

module.exports = {
    entry: './src/index.js',
    output: {
        path: path.resolve(__dirname, 'dist'),
        filename: 'bundle.js'
    },
    module: {
        rules: [
            {
                test: /\.js$/,
                exclude: /node_modules/,
                use: {
                    loader: 'babel-loader'
                }
            }
        ]
    }
};
3.	Then, in your package.json, add a script to run Webpack:
"scripts": {
    "build": "webpack"
  },
4.	Finally, you can run the build script by running npm run build in your terminal, and webpack will create a bundle.js file in the dist directory.
Naming Conflicts
Module bundlers can potentially introduce naming conflicts. They occur when two or more modules use the same variable or function name. These conflicts can cause unexpected behavior and errors in your code. To resolve these conflicts, you can use a technique called "tree shaking", which is a way of removing unused code from the final bundle. Many module bundlers support the use of namespaces or scoping to reduce the chance of naming conflicts.
Popular Module Bundlers
•	Webpack.
•	Esbuild.
•	Rollup.

7. Testing and Test-Driven Development (TDD):
Test-Driven Development (TDD) is a software development method in which testing is done before coding is written. This means that development begins with writing tests that define how a particular function or module should work.
In layman’s terms, Test Driven Development (TDD) is a software development practice that focuses on creating unit test cases before developing the actual code. It is an iterative approach combining programming, unit test creation, and refactoring.
•	The TDD approach originates from the Agile manifesto principles and Extreme programming.
•	As the name suggests, the test process drives software development.
•	Moreover, it’s a structuring practice that enables developers and testers to obtain optimized code that proves resilient in the long term.
•	In TDD, developers create small test cases for every feature based on their initial understanding. The primary intention of this technique is to modify or write new code only if the tests fail. This prevents duplication of test scripts.
Test Driven Development (TDD) Examples
1.	Calculator Function: When building a calculator function, a TDD approach would involve writing a test case for the “add” function and then writing the code for the process to pass that test. Once the “add” function is working correctly, additional test cases would be written for other functions such as “subtract”, “multiply” and “divide”.
2.	User Authentication: When building a user authentication system, a TDD approach would involve writing a test case for the user login functionality and then writing the code for the login process to pass that test. Once the login functionality works correctly, additional test cases will be written for registration, password reset, and account verification.
3.	E-commerce Website: When building an e-commerce website, a TDD approach would involve writing test cases for various features such as product listings, shopping cart functionality, and checkout process. Tests would be written to ensure the system works correctly at each process stage, from adding items to the cart to completing the purchase.
Three Phases of Test Driven Development
1.	Create precise tests: Developers need to create exact unit tests to verify the functionality of specific features. They must ensure that the test compiles so that it can execute. In most cases, the test is bound to fail. This is a meaningful failure as developers create compact tests based on their assumptions of how the feature will behave.
2.	Correcting the Code: Once a test fails, developers must make the minimal changes required to update the code to run successfully when re-executed.
3.	Refactor the Code: Once the test runs successfully, check for redundancy or any possible code optimizations to enhance overall performance. Ensure that refactoring does not affect the external behavior of the program.
The image below represents a high-level TDD approach toward development:
 
8. Browser APIs and DOM Manipulation:
JavaScript interacts with the browser and web pages through Browser APIs and DOM Manipulation.
Browser APIs:
•	These are built-in interfaces provided by the browser that allow you to access various functionalities like:
o	DOM API: Manipulate the structure, content, and style of a web page (more details below).
o	Fetch API: Make network requests to retrieve data from servers.
o	Web Storage API: Store data locally in the browser (e.g., Local Storage, Session Storage).
o	Geolocation API: Access the user's geographic location.
o	Canvas API: Draw graphics and animations on the page.
o	Web Audio API: Work with audio data in the browser.
o	WebRTC API: Enable real-time communication (e.g., video calls).
DOM Manipulation:
•	The Document Object Model (DOM) represents the HTML structure of a web page as a tree-like structure, where each HTML element is a node in the tree.
•	JavaScript can use the DOM API to:
o	Select elements: Access specific elements using methods like getElementById, querySelector, and querySelectorAll.
o	Modify content: Change the text content of an element using properties like innerText or textContent.
o	Manipulate attributes: Add, remove, or modify attributes of elements (e.g., src, class, id).
o	Change styles: Modify the visual appearance of elements by manipulating their CSS styles.
o	Add/remove elements: Dynamically create new elements and insert them into the DOM, or remove existing elements.
o	Handle events: Respond to user interactions like clicks, mouse movements, and keyboard presses.
Example:
JavaScript
// Select an element by its ID
const myElement = document.getElementById("myElement");

// Change the text content of the element
myElement.textContent = "Hello, world!";

// Add a new class to the element
myElement.classList.add("highlight");

// Add an event listener to the element
myElement.addEventListener("click", function() {
  alert("Element clicked!");
});
Important Points:
•	DOM Manipulation can be expensive: Excessive DOM manipulation can negatively impact website performance.
•	Modern JavaScript frameworks: Libraries like React, Vue, and Angular provide more efficient ways to manage the DOM by using a virtual DOM.
•	Understanding CSS selectors: Being proficient in CSS selectors is crucial for effectively selecting elements in the DOM.
Practical Examples Comparing the BOM and DOM:
•	Accessing Window Properties with the BOM:
// Get the width and height of the browser window
const windowWidth = window.innerWidth || document.documentElement.clientWidth;
const windowHeight = window.innerHeight || document.documentElement.clientHeight;
console.log(`Window dimensions: ${windowWidth} x ${windowHeight}`);

// Scroll to a specific position
window.scrollTo(0, 0);
•	Manipulating DOM Elements with the DOM:
// Change the background color of an element
const element = document.getElementById("myElement");
element.style.backgroundColor = "blue";

// Create a new element and append it to the document
const newElement = document.createElement("div");
newElement.textContent = "New Element";
document.body.appendChild(newElement);

