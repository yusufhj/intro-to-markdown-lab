Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

1. Basic syntax

const functionName = (params) => {
  // code to be executed
}

const: const should be used whenever a function expression is assigned to a variable.
The function name: The name you choose for the function.
Parameters: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
The arrow syntax: Indicates that this will be a function.
The body: The statements that make up the function itself. Surrounded by curly braces.

Example:

const greet = (name) => {
  console.log("Hello, " + name + "!");
}

Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

2. *Calling a function*

To execute the function, you *call* or *invoke* it by using its name followed by parentheses.

Example:

greet('Alice'); // Outputs: Hello, Alice!

3. Return values

Functions can process data input and output a value using the return keyword.

Example: 

const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6

For more information on functions and how they are used in JS, check out the MDN docs. 
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions

# h1
## h2
### h3
#### h4
##### h5
###### h6

This text is **bold**. This text is also __bold__.

This text is in *italics*. This text is also in _italics_.

This text is ***bold and italicized***. This text is also ___bold and italicized___.

**const**: ...
**The function name**: ...
**Parameters**: ...
**The arrow syntax**: ...
**The body**: ...

* Item 1
* Item 2
  * Subitem 2.1
  * Subitem 2.2
    * Subitem 2.2.1

1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2

Use the `console.log()` function to print values to the console.

```javascript
const printItem = (item) => {
  console.log(item);
}
```

[Google](https://www.google.com)

This is [a reference][example].

[example]: http://www.example.com/

> This is a blockquote.

> First level of blockquote.
>> Nested blockquote.
>>> Another nested blockquote.

![some alt text](www.url_to_an_image.com/image)

![Computer with Code](https://images.unsplash.com/photo-1587620962725-abab7fe55159?auto=format&fit=crop&q=80&w=1631&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

![Computer with Code](./assets/james-harrison-unsplash.jpg)

| Syntax | Description |
| ------ | ----------- |
| Header | Title |
| Paragraph | Text |

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

This text has been ~~redacted~~. 

``` JavaScript
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
greet('Alice'); // Outputs: Hello, Alice!`

const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6

```