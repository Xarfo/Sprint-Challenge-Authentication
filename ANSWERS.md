<!-- Answers to the Short Answer Essay Questions go here -->

What is the purpose of using _sessions_?

```
Sessions store information that is needed for the persistence of data. Sessions live within the server and helps retrieve data from the database when presented with a cookie and session_id by the client.
```

What does bcrypt do to help us store passwords in a secure manner.

```
Bcrypt is a library on NPM that makes it easy to `hash` and `compare` passwords in Node enviroment. Bycrypt converts plain-text password into a long string of characters thus hashing or concealing the password.
```

What does bcrypt do to slow down attackers?

```
bcrypt spends a significant amount hashing each password multip;e rounds, recommended of 12 rounds and extra layer that adds time so that brute force attacks become less effective.
```

What are the three parts of the JSON Web Token?

```
-header: type of token and hash algorithm

-payload: user info and claims

-signature: created from header, payload, and secret
```