# Dependencies:

- express: Node.js's framework that provides a robust set of features for web and mobile applications.

- @types/express: This package contains type definitions for Express.

- dotenv: This module loads environment variables from a .env file into process.env. Storing configuration in the environment.

- nodemon: This tool helps to develop Node.js based applications by automatically restarting the node aplication when file canges in the directory are detected.

- typescript: Adds optional types to JavaScript that support tools for large-scale JavaScrpt applications for any browser, for any host, on any OS. TypeScript compiles to readable, standards-based JavaScript. Try it out at the playground, and stay up to date via our blog and Twitter account.  

- ts-node: Allow the execution and REPL for node.js, with source map and native ESM support.

- @types/node: This package contains type definitions for Node.Js

- eslint: Is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code.

- eslint-config-standard-with-typescript: An ESLint shareable config for TypeScript that is based on eslint-config-standard and has TypeScript specific rules from @typescript-eslint/eslint-plugin.

- jest: Used for JavaScript Testing.

- ts-jest: A Jest transformer with source map support that lets you use Jest to test projects written in TypeScript.

- @types/jest: TypeScript definitions for Jest.

- supertest: HTTP assertions made easy via superagent. It provides a high-level abstraction for testing HTTP, while still allowing you to drop down to the lower-level API.

- webpack: A module bundler. Its main purpose is to bundle JavaScript files for usage in a browser, yet it is also capable of transforming, bundling, or packaging just about any resource or asset.

- webpack-node-externals: Webpack allows you to define externals - modules that should not be bundled.

- webpack-shell-plugin: This plugin allows you to run any shell commands before or after webpack builds. This will work for both webpack and webpack-dev-server.

- webpack-cli: Provides a flexible set of commands for developers to increase speed when setting up a custom webpack project. 

- concurrently: Runs commands concurrently.

- helmet: Helps you secure your Express apps by setting various HTTP headers.

- cors: Provides a Connect/Express middleware that can be used to enable CORS with various options.

- mongoose: A MongoDB object modeling tool designed to work in an asynchronous environment. 


# Scripts:

- build: Creates the build for development.

- build:prod: Creates the build for production.

- start: Creates/updates 'diste' folder..

- dev: 
     - Calls the Typescript compiler with '--watch' parameter to react to compile status. 
     - Calls 'swagger'.
     - Executes index.js from 'dist' folder.

- test: Executes Jest test.

- serve:coverage: Executes 'test', show coverage & serves.

- swagger: Generates a Swagger file.

# Environment Variables: 

PORT=8000