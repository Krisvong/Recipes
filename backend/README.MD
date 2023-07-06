Project Setup
1. Initialize NPM project
To initialize a new npm project with default settings, run the following command:

npm init -y
This will create a new npm project in the current directory.

2. Install regular dependencies
To install the regular dependencies for your web application, run the following command:

npm install express helmet cors
This will install the express, helmet, and cors packages, which are commonly used for building web applications in Node.js.

3. Install TypeScript type definitions
To enhance TypeScript type checking and editor support, install the TypeScript type definitions for the dependencies by running the following commands:

npm install -D @types/node
npm install -D @types/express
npm install -D @types/cors
These commands will install the @types/node, @types/express, and @types/cors packages as dev dependencies.

4. Install ts-node (optional)
If you want to directly run TypeScript files without transpiling them to JavaScript, you can install ts-node as a dev dependency:

npm install -D ts-node
5. Install ESLint and related packages (optional)
For linting and code formatting, you can install ESLint and related packages with the following command:

npm install -D eslint @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-config-prettier
These packages are essential for setting up ESLint with TypeScript support and integrating it with Prettier.

npm init @eslint/config
Need to install the following packages:
  @eslint/create-config@0.4.5
Ok to proceed? (y) 
✔ How would you like to use ESLint? · style
✔ What type of modules does your project use? · esm
✔ Which framework does your project use? · none
✔ Does your project use TypeScript? · No / Yes
✔ Where does your code run? · browser, node
✔ How would you like to define a style for your project? · guide
✔ Which style guide do you want to follow? · standard-with-typescript
✔ What format do you want your config file to be in? · JSON
Checking peerDependencies of eslint-config-standard-with-typescript@latest
The config that you've selected requires the following dependencies:

eslint-config-standard-with-typescript@latest @typescript-eslint/eslint-plugin@^5.50.0 eslint@^8.0.1 eslint-plugin-import@^2.25.2 eslint-plugin-n@^15.0.0 eslint-plugin-promise@^6.0.0 typescript@*
✔ Would you like to install them now? · No / Yes
✔ Which package manager do you want to use? · npm

npm install -D prettier

npm install -D nodemon

npm install rimraf

npm i -D @types/dotenv

npm i -D dotenv  
