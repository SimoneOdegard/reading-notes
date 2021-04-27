# Read 07

## Review, Research, and Discussion

**Write the following steps in the correct order:**

  - Register your application to get a client_id and client_secret
  - Ask the client if they want to sign in via a third party
  - Redirect to a third party authentication endpoint
  - Make a request to a third-party API endpoint
  - Receive authorization code
  - Make a request to the access token endpoint
  - Receive access token
  [resource](https://auth0.com/docs/flows/authorization-code-flow#how-to-implement-it)

**What can you do with an authorization code?** They are used for any transaction or entry that has restrictions on which users are entitled to access. [resource](https://www.investopedia.com/terms/a/authorization-code.asp#:~:text=Authorization%20codes%20are%20used%20for,vendor%2C%20that%20authorizes%20the%20sale.)

**What can you do with an access token?** Access tokens are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a specific application to access specific parts of a user’s data. [resource](https://www.oauth.com/oauth2-servers/access-tokens/#:~:text=Access%20tokens%20are%20the%20thing,in%20transit%20and%20in%20storage.)

**What’s a benefit of using OAuth instead of your own basic authentication?** It allows limited access to the user's data and allows accessing when authorization tokens expire. [resource](https://www.tutorialspoint.com/oauth2.0/oauth2.0_overview.htm#:~:text=Advantages%20of%20OAuth%202.0&text=It%20allows%20limited%20access%20to,implement%20and%20provides%20stronger%20authentication.)

## Term

- **Client ID** "The client_id is a public identifier for apps. Even though it’s public, it’s best that it isn’t guessable by third parties, so many implementations use something like a 32-character hex string. It must also be unique across all clients that the authorization server handles. If the client ID is guessable, it makes it slightly easier to craft phishing attacks against arbitrary applications." [resource](https://www.oauth.com/oauth2-servers/client-registration/client-id-secret/)
- **Client Secret** "The client_secret is a secret known only to the application and the authorization server. It must be sufficiently random to not be guessable. A great way to generate a secure secret is to use a cryptographically-secure library to generate a 256-bit value and converting it to a hexadecimal representation." [resource](https://www.oauth.com/oauth2-servers/client-registration/client-id-secret/)
- **Authentication Endpoint** Endpoint authentication is a security mechanism designed to ensure that only authorized devices can connect to a given network, site or service. [resource](https://whatis.techtarget.com/definition/endpoint-authentication)
- **Access Token Endpoint** "The token endpoint is where apps make a request to get an access token for a user. This section describes how to verify token requests and how to return the appropriate response and errors." [resource](https://www.oauth.com/oauth2-servers/access-tokens/)
- **API Endpoint** "an endpoint is one end of a communication channel. When an API interacts with another system, the touchpoints of this communication are considered endpoints. For APIs, an endpoint can include a URL of a server or service." [resource](https://smartbear.com/learn/performance-monitoring/api-endpoints/#:~:text=Simply%20put%2C%20an%20endpoint%20is,of%20a%20server%20or%20service.)
- **Authorization Code** "An authorization code is an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space." [resource](https://www.investopedia.com/terms/a/authorization-code.asp#:~:text=What%20Is%20an%20Authorization%20Code,into%20a%20security%2Dprotected%20space.)
- **Access Token** Access tokens are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a specific application to access specific parts of a user’s data. [resource](https://www.oauth.com/oauth2-servers/access-tokens/#:~:text=Access%20tokens%20are%20the%20thing,in%20transit%20and%20in%20storage.)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**
1. Authorization vs Authentication
2. Header and what it is used for
3. OAuth

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
1. JWT/tokens
2. Authorization
3. Decoding

**What are you most excited about trying to implement or see how it works?** Understanding more about JWT as well as tokens in general.

## Readings

[JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo) (video)
[Intro to JWT](https://jwt.io/introduction/)
[Are JWTs Secure](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

[<== Back](https://simoneodegard.github.io/reading-notes/)