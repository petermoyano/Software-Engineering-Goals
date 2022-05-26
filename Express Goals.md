# Express Goals
## Intro to Node
### JavaScript Promises
-   Review the callback pattern for asynchronous code in JavaScript
-   Define what a promise is
-   Use promises to manage asynchronous code
-   Compare and contrast promises with the callback pattern
-   Explore the Promise function in detail

### ES2017 Async Functions


-   Explain what the async keyword does
-   Explain what the await keyword does
-   Manage asynchronous code using async / await
-   Refactor code using other patterns (e.g. callbacks, promises) to async / await

### Intro to Node
* Explain what is npm and why do we use it.
* Use the process library: process.env and process.argv
* Learn what the Module system is used for.
* Node callbacks and the fs module

### Testing with Jest
- Write unit tests using Jest
- Learn to orginize our tests with test and describe
- Learn to use expectations and matchers
- Explain why we use Before / After keywords

## Express fundamentals
### Express Intro
- What is Express and how do you launch a server
- Explain what route handlers do and talk about the request-response cycle
- Learn to recieve and send JSON and work with URL parameters
- Explain what the error handling process is; global errors, 404 errors and custom errors
- Debugging express apps using chrome dev tools
### Express Routing and middleware
- Learn the benefits of express routing
- Explain why do we need Middleware: Authorizations and next keyword
- Perform Integration tests in Express, testing CRUD operations, debugging

## Express and PostgreSQL
### Node-pg intro
-   Use pg to connect and execute SQL queries
-   Explain what SQL injection is and how to prevent it with pg
-   Examine CRUD on a single resource with Express and pg

### Node-pg relationships
-   Work with 1:M relationships in pg
-   Work with M:M relationships in pg
-   Handle missing data by sending 404s

### Database OO Design Patterns
-   Refactor our Express apps to separate view logic (routing) from model logic (data)
-   Compare different OO designs for interfacing with our database
-   Borrow useful ideas from ORMs to build our own model layers!

## Intermediate Express
### Hashing and JWT with Node
-   Hash passwords with Bcrypt
-   Using JSON web tokens for API authentication
-   Use middleware to simplify route security

### API Validation with JSON Schemas
-   Understand how and why to validate APIs
-   Validate our JSON APIs using jsonschema

### Express Testing Practices
-   Revisit some essential concepts with testing like test driven development, mocking, Continuos Integration, End to End tests
-   Understand what mocking is
-   Examine end to end tests with Cypress

## Express Wrapup
* Pug; popular templating system
* Helmet: Provides tools for dealing with CSRF and other concerns
* Passport.js : Authentication/Login, Also provides login via Facebook, Twitter, etc
* Moment.js: Convenient functions for date manipulation & conversion. Provides “humanized” dates, like “a few minutes ago”, “yesterday”
* Validator.js: String validators for our inputs
* Lodash: Useful set of small utility functions for common actions on arrays, objects, functions
* Briefly explain what web sockets are.