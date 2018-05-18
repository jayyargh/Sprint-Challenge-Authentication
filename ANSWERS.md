<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.

> Middleware is code that is used by the server in between client/server requests/responses.

> Sessions is a package that keeps track of whether a user is logged in or not.

> bcrypt will take a password, hash it and a salt to it thus encrypting it.

> JWT is jsonwebtoken package, which uses tokens that can be created and destroyed to simulate a login/logout environment.

2.  What does bcrypt do in order to prevent attacks?

> It adds a random salt to a known string and when an attempt is made to login it checks to make sure the generated token matches the stored token.

3.  What are the three parts of the JSON Web Token?

> the header, the payload, and the signature
