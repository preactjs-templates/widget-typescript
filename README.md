Preact widget-typescript starter project
Documentation
This is a TypeScript version of the default template for preact-cli.
For Preact: General information about how to work with Preact, not specific to this template
Usage
$ npm install -g preact-cli
$ preact create widget-typescript my-project
$ cd my-project
$ npm install
$ npm run dev
Development server runs on port 8080. If the default port is already in use on your machine it will start the development server on a random port.

Commands
npm install: Installs dependencies

npm run start: Runs serve or dev, depending on NODE_ENV value. Defaults to dev server

npm run dev: Run a development, HMR server

npm run build: Production-ready build

npm run lint: Pass TypeScript files using ESLint

npm run test: Run Jest and preact-render-spy for your tests

How to Test
The typescript template provides a basic test setup with Jest and preact-render-spy. You are free to change preact-render-spy with any other assertion library. The advantage of it is that it supports a similar terminology and feature set as the Enzyme library for testing React applications.

You can run all additional Jest CLI commands with the npm run test command as described in the Jest docs. For example, running jest in watch mode would be :

npm run test -- --watch instead of jest --watch