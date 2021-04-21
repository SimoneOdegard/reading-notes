# Read 02

1. **What’s the difference between PUT and PATCH?** "PUT is a method that uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource. PATCH is a method that supplies a set of instructions to modify the resource."

[resource](https://en.wikipedia.org/wiki/Patch_verb#:~:text=The%20main%20difference%20between%20the,instructions%20to%20modify%20the%20resource.)

2. **Provide links to 3 services or tools that allow you to “mock” an API for development like json-server**
[Mirage](https://miragejs.com/)
[Jest](https://jestjs.io/)
[Cypress](https://www.cypress.io/)

3. **Compare and contrast Swagger and APIDoc.js**
- Swagger is more popular
- Swagger uses more from Info and UI prospective
- Both require documentation content on implemented method as customize comment data. You can write in separate resource files
- APIDoc.js you can isolate the layer for documentation modification
- Swagger docs use plain .json which means it can be parsed
- Swagger let's you switch APIDoc.js to Swagger at anytime

[resource](https://www.asptricks.net/2019/04/apidoc-vs-swagger-for-node-app.html)

4. **Which HTTP status codes should be sent with each type of (un)successful API call?**
1xx: Informational
2xx: Success
3xx: Redirection
4xx: Client Error
5xx: Server Error

[resource](https://www.restapitutorial.com/httpstatuscodes.html)

5. **Compare and contrast SOAP and ReST**
**REST**: Representational State Transfer
- All about simplicity
- Facilitates client-server communcations and architectures.
- Use single uniform interface
- Optimized for the web
- Excellent performance and scalability

**SOAP**: Simple Object Access Protocol
- Better security
- Reliable messaging functionality
- ACID compliance which reduces anomalies and protects the integrity of a database. ACID is conservative and great for handling sensitive transactions

[resource](https://www.upwork.com/resources/soap-vs-rest-a-look-at-two-different-api-styles?utm_source=google&utm_medium=cpc&utm_campaign={campaign}&utm_content=111050689163&utm_term=&vt_cmp={campaign}&vt_adg=111050689163&vt_src=google&vt_kw=&vt_device=c&utm_source=google&utm_campaign={campaign}&utm_medium=paidsearch&gclid=Cj0KCQjw9_mDBhCGARIsAN3PaFO4uSBNgktxck4ufdeqof0Y1Q_1xw3g7VlFAO_xVGqrI4W2qCSOmDUaAvb9EALw_wcB)

## Terms
- **Web Server:** It runs websites. A web server receives HTTP requests from a client and provides an HTTP response. [resource](https://www.digitalocean.com/community/tutorials/how-to-create-a-web-server-in-node-js-with-the-http-module#:~:text=A%20web%20server%20receives%20HTTP,or%20JSON%20from%20an%20API.&text=js%20allows%20developers%20to%20use,to%20write%20front%2Dend%20code.)
- **Express:** The most popular Node web framework. It is fast, minimal, and flexible. Express provides a thin layer of fundamental web application features. Many popular frameworks are based on Express. [resource](https://expressjs.com/)
- **Routing:** Routing is a way of organizing and managing application states. [resource](https://stackoverflow.com/questions/10075507/what-does-javascript-routing-buy-you#:~:text=Routing%20is%20a%20way%20of,%2D%2Dwhile%20maintaining%20application%20persistence.)
- **WRRC:** Web Request Response Cycle

1. **Which 3 things had you heard about previously and now have better clarity on?**
- express: How express is a lightweight framework that is very popular. It's so popular that many frameworks are based on express.
- npm: consists of three components, the website, the command line interface, and the registry. You can also share packages and collaborate with others.
- CI/CD: How the CI can show what changes can be integrated into the branch while CD is developing a way to release code at anytime.

2. **Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
- Webhooks
- TDD
- Writing tests

3. **What are you most excited about trying to implement or see how it works?**
- Writing tests! I feel like today I was getting a better understanding of writing tests but I am struggling to get my tests to pass! I'm ready to learn more about it.

**Readings**
- [Express/Node introduction](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)
- [What is NPM](https://docs.npmjs.com/about-npm)
- [What is TDD](https://www.agilealliance.org/glossary/tdd/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'tdd))~searchTerm~'~sort~false~sortDirection~'asc~page~1))
- [CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)