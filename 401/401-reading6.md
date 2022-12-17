# Authentication

[Return to Home](https://sethppierce.github.io/reading-notes)

## Questions

### Securing Passwords

Explain to a non-technical friend how you would safely hash and store a password.

first generate a secure form of the password using a tool, and then store that in your database rather than the actual password.

What is Bcrypt?

Bcrypt is a password hashing function

Why might you use something like Bcrypt?

You might use something like Bcrypt to secure passwords in order to protect against unauthorized access to user accounts.

### Basic Auth

What is Basic Authentication?

Basic Authentication is a simple authentication scheme built into the HTTP protocol that allows a web server to request a username and password

What properties are necessary in the header of a Basic Auth request?

Authorization: Basic credentials

How are username:password in Basic Auth encoded?

with base64

### OWASP auth cheatsheet

Define the authentication process to a non-technical recruiter.

The authentication process involves verifying a user's identity through the use of a login like a username or password.

How should your error messaging respond (both HTTP and HTML)? Why?

It shouldn't be the specific reason something threw an error, to protect the users info