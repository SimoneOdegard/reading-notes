# Read 06

## Review, Research, and Discussion

**Explain what a “Singleton” is (in Computer Science terms)** A singleton is a pattern restricting instantiation to one instance. You would use this when you need only one object to coordinate actions across the system. [wikipedia](https://en.wikipedia.org/wiki/Singleton_pattern)

**Explain how the Singleton pattern can be used with Node modules, specifically with classes** If you know you want to have one instance, then this pattern is for you. One is dealing with database connections. It could also be a resource manager or a global lookup for values. [logrocket](https://blog.logrocket.com/design-patterns-in-node-js/) and [digitalocean](https://www.digitalocean.com/community/tutorials/js-js-singletons)

**If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?** I need to determine what kind of middleware is need and what I need to build. I also know I need to have three arguments, request, response, and next lifecycle methods. [medium](https://medium.com/@selvaganesh93/how-node-js-middleware-works-d8e02a936113)

## Term

- **Router Middleware** Router is used to manage incoming requests coming from the middleware. It routes your requests to the correct handler/code. [medium](https://medium.com/@selvaganesh93/how-node-js-middleware-works-d8e02a936113#:%7E:text=A%20middleware%20is%20basically%20a,once%20your%20middleware%20code%20completed.)
- **Dynamic Module Loading** "A mechanism by which a computer program can, run, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory." [wikipedia](https://en.wikipedia.org/wiki/Dynamic_loading#:~:text=Dynamic%20loading%20is%20a%20mechanism,unload%20the%20library%20from%20memory.)
- **Singleton Pattern** A singleton is a pattern restricting instantiation to one instance. You would use this when you need only one object to coordinate actions across the system. [wikipedia](https://en.wikipedia.org/wiki/Singleton_pattern)
- **CRUD -> REST Method Matches**
  - REST | CRUD
  - GET | read
  - PUT | update
  - POST | create
  - DELETE | delete
- **Mock Testing** "An approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. The dependencies are replaced with objects that simulate the behavior of the real ones." [devopedia](https://devopedia.org/mock-testing#:~:text=Mock%20testing%20is%20an%20approach,behaviour%20of%20the%20real%20ones.)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**
1. Authentication
1. Router Middleware
1. REST and CRUD and how they relate to each other

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
1. Cryptographic hash algorithm and BCrypt
1. Dynamic Module Loading
1. Singleton Pattern

**What are you most excited about trying to implement or see how it works?** BCrypt hashing seems super interesting! I'm interesting in understanding how passwords are hashed and understanding how that whole process works.

## Readings

- [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)
- [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)
- [OWASP auth cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)
- [bcryptdocs](https://www.npmjs.com/package/bcrypt)

[<== Back](https://simoneodegard.github.io/reading-notes/)