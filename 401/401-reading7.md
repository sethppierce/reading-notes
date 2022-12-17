# Bearer Authorization

[Return to Home](https://sethppierce.github.io/reading-notes)

## Questions

### Intro to JWT

What is a JSON Web Token (JWT)?

A JSON Web Token (JWT) is a JSON-based open standard for creating access tokens.

When should we use JSON Web Tokens?

We should use JSON Web Tokens when we want to securely transmit information between parties.

Claims are expected in which structural component of a JWT?

Claims are expected in the payload of a JWT.

### Are JWTs Secure?

If I get a JWT and I can decode the payload, how can we call that secure?

Because the secret has to match.

If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

To secure a JWT, the sender and receiver must both know the secret that is used to create the signature.

Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

It's like an elementary school made up language, both parties need to know the secret behind it to know what it means

### JWTs Explained

Why use JWT?

JWTs are used because they provide a simple and secure way to transmit information between parties.

JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

It has everything we need in one place.

What are the three components (the structure) of a JWT signature?

The three components of a JWT signature are the header, the payload, and the signature. 