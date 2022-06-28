# Intro to TypeScript
- [Hello World](https://github.com/thuyanduong/typescript-hello-world)
- [React Connect Four](https://github.com/thuyanduong/React-Connect-Four)

## Essential Questions
- What is TypeScript?
- What is a dynamically typed language? What are some examples?
- What is a statically typed language? What are some examples?
- What are the benefits of dynamically typed languages vs statically typed languages?
- What does it mean that TypeScript is a superset of JavaScript?

## Adding TypeScript to vanilla JavaScript
- We need to create a node application with `npm init`
- `npm install typescript` to install a TypeScript compiler
- What is a compiler? 
  - Create `.ts` files
  - `tsc index.js` to compile one file  
  - `tsc --init` to set up TypeScript configuration
  - `tsc` to compile all `.ts` file in a project

## Typing
- Primative data types
- Function parameters
- Function returns
- Objects
- **Type Alias**

## Adding TypeScript to React
- `npm install --save typescript @types/node @types/react @types/react-dom @types/jest`
- `tsc --init`
- `tsconfig.json` { "noImplicitAny": false, "jsx": "react-jsx" }
