# Read 03

## Review, Research, Discussion

**Name 3 real world use cases where you’d want to change the request with custom middleware** 
1. Log in/Authentication
1. Messages
1. Sending objects

**True or false: The route handler is middleware?** False, they are not middleware by definition. They can become middleware. [stackoverflow](https://stackoverflow.com/questions/58925276/what-is-the-difference-between-a-route-handler-and-middleware-function-in-expres#:~:text=They%20are%20not%20middleware%20functions,they%20are%20only%20handler%20functions)

**In what ways can a middleware function end the process and send data to the browser?** If you need to end the middleware process early, do not call ```next()```. You can also use ```res.end```, ```res.send```, ```res.render``` or a method that calls ```res.end``` to end the process. [stackoverflow](https://stackoverflow.com/questions/33648905/after-sending-response-how-to-end-the-current-request-processing-in-node-expres)

**At what point in the request lifecycle can you “inject” middleware?** After a request is made but before there is a response from the server.

**What can cause express to error with “Request headers sent twice, cannot start a second response”** You told the script to respond twice. It will not start a second response [reddit](https://www.reddit.com/r/learnjavascript/comments/bemn1l/error_cant_set_headers_after_they_are_sent/)

## Terms
**Middleware** "Middleware is a software that acts as an intermediary between two applications or services to facilitate their communication." [freecodecamp](https://www.freecodecamp.org/news/what-is-middleware-with-example-use-cases/)
**Request Object** "Request object allows you to submit a POST or GET request to an URL. It provides a way to make REST API requests to another URL." [BranchCMS](https://www.branchcms.com/learn/docs/developer/twig/request-object)
**Response Object** "It is the object which communicates between the server and the output which is sent to the client"[4guysfromrolla](https://www.4guysfromrolla.com/webtech/faq/Beginner/faq3.shtml)
**Application Middleware** "Application level middleware are bound to an instance of express, using ```app.use()``` and ```app.VERB()```." [resource](https://stackoverflow.com/questions/29457008/whats-the-difference-between-application-and-router-level-middleware-when-rou#:~:text=Application%20level%20middleware%20are%20bound,to%20an%20instance%20of%20express.)
**Routing Middleware** "Router level middleware work just like application level middleware except they are bound to an instance of ```express.Router()```" [resource](https://stackoverflow.com/questions/29457008/whats-the-difference-between-application-and-router-level-middleware-when-rou#:~:text=Application%20level%20middleware%20are%20bound,to%20an%20instance%20of%20express.)
**Test Driven Development** A process that has software requirements that runs test cases before the software is fully developed. [wikipedia](https://en.wikipedia.org/wiki/Test-driven_development)
**Behavioral Testing** A branch of TDD. It uses human-readable descriptions of software user requirements as the basis for software tests. [medium](https://medium.com/javascript-scene/behavior-driven-development-bdd-and-functional-testing-62084ad7f1f2)

## Preview
**Which 3 things had you heard about previously and now have better clarity on?**
- Middleware
- express.Router
- Route handlers

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
- I need a review with Classes
- Static methods and properties
- More about middleware and how to use them with routes

**What are you most excited about trying to implement or see how it works?** Doing more with express.Routers and middleware

[<== Back](https://simoneodegard.github.io/reading-notes/)