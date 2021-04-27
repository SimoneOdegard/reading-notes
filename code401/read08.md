# Read 08

## Review, Research, and Discussion

**When is Basic Authorization used vs. Bearer Authorization?** Basic is when you access the API directly with your username and password credentials. So the user would choose Basic Auth to fill-in the username and password. Bearer is where you need to make 2 call: one to get the bearer token and one to get the data. When you have the bearer token, you can reuse it for up to 60minutes. Bearer is the recommended Auth method to do whenever possible. Great for scripting, developing an external app, or integrating with external tools. [mega](https://community.mega.com/t5/REST-API/Basic-Auth-vs-Bearer-Token/td-p/23476)

**What does the JSON Web Token package do?** JWT defines a compact and self-contained way to securely transfer information between two parties as a JSON object. All JWTs are tokens but not all tokens are JWTs. JWT contains information about an entity to avoid querying a database more than once. [auth0](https://auth0.com/docs/tokens/json-web-tokens#use)

**What considerations should we make when creating and storing a SECRET?** When generating a secret, it should be secure. One way to do that is using a cryptographically secure library. Using this will convert it to a hexadecimal representation. You'll want to never include your secret in a public app. Make the secret visually different from the ID. Also, do not store the secret in plain text, only store in an encrypted or hashed version. [oauth](https://www.oauth.com/oauth2-servers/client-registration/client-id-secret/)

## Term

- **encryption** This is a method hiding information's true meaning by converting it into a secret code. [searchsecurity](https://searchsecurity.techtarget.com/definition/encryption)
- **token** "a token is a single element of a programming language. There are five categories of tokens: 1 constants, 2 identifiers, 3 operators, 4 separators, and 5 reserved words" [techterms](https://techterms.com/definition/token#:~:text=In%20programming%2C%20a%20token%20is,%2C%20and%205%20reserved%20words.&text=Operators%2C%20such%20as%20%2B%2C%20%2D,of%20nearly%20all%20programming%20languages.)
- **bearer** "Bearer Token is an opaque string, not intended to have any meaning to clients using it. Some servers will issue tokens that are a short string of hexadecimal characters, while others may use structured tokens such as JSON Web Tokens." [oauth](https://oauth.net/2/bearer-tokens/)
- **secret** "Any value that an attacker could use to impersonate the user in an authentication protocol." [nist](https://csrc.nist.gov/glossary/term/Authentication_Secret)
- **JSON Web Token** A compact, URL-safe way to securely transfer information between two parties as a JSON object. [jwt](https://jwt.io/introduction/)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**
1. JWT
1. secret
1. encryption

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
1. RBAC - "the idea of assigning system access to users based on their role in an organization. It's important to remember that not every employee needs a starring role."[csoonline](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)
1. Bearer
1. More about tokens in general!

**What are you most excited about trying to implement or see how it works?** Implementing RBAC seems super cool! In my project for 201 we thought of having an admin login and it seems like this is something that would do that.

## Readings
[RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)
[5 steps to RBAC](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)
[wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)

[<== Back](https://simoneodegard.github.io/reading-notes/)