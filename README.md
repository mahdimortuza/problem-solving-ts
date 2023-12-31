# What are some benefits of using TypeScript over JavaScript in a project?

- To write less bug
- To define types for JavaScript
- To make the code understandable for the browser
- To make the code better readable

# What is the purpose of the optional chaining (?.) and nullish coalescing (??) operators in TypeScript, and how do they work? Provide an example for each

- Optional chaining is used to to handle null or undefined values
- Nullish coalescing is used to make a default value null or undefined

# How do you handle asynchronous operations in TypeScript, and what are the advantages of using async/await over callbacks or Promises?

- We handle asynchronous operations in TypeScript by using async/await or callbacks or promises.
- There are several advantages of using async/await over callbacks or Promises. for example, better readability, error handling, debugging and many more.

# How can you use TypeScript's enums, and what are their advantages?

- Enum can be defined using the enum keyword.
- It has various using advantage. For example, it helps to define strictly typed variable, better readability, type safety, easy use case and so on.

# Explain the role of type guards in TypeScript and provide an example of a custom type guard.

- Type guards narrow down a variable and its type within a certain block of code.
- we use typeOf, instanceOf for making custom type guard.

# Can you give an example of how to use "readonly" properties in TypeScript?

- readonly property is used to prevent change the type of a variable.
- Example:
  interface {
  readonly name: string
  }

# Explain what a union type is in TypeScript and provide an example of its usage.
- Union type is used to assign more than one type in a variable
- Example, type Id = string | number