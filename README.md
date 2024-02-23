TypeScript Node.js Hello World
This is a simple example to set up a Node.js project with TypeScript.

Prerequisites
Node.js installed

TypeScript installed globally:

npm install -g typescript
Visual Studio Code installed

Steps
Install Node.js from nodejs.org

Install TypeScript globally using npm:

npm install -g typescript
Install Visual Studio Code from code.visualstudio.com

Read about generating tsconfig.json from here

Read a tutorial on TypeScript Hello World from here

Generate tsconfig.json by running:

tsc --init
If you're using Windows Powershell and encounter issues running tsc, open Powershell in Administrator mode and run:

Set-ExecutionPolicy RemoteSigned
Make it a Node.js project by running:

npm init -y
Install types for Node.js:

npm i @types/node -D
Create a .gitignore file to ignore unnecessary files:

Copy code
node_modules/
dist/
Create a TypeScript file (e.g., app.ts) and add the following code:

typescript
Copy code
const message: string = "Hello World";
console.log(message);
Transpile TypeScript to JavaScript by running:

tsc
Run the transpiled JavaScript by running:

node app
Additional Resources
TypeScript Documentation
Visual Studio Code TypeScript Documentation