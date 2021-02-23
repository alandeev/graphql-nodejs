# My frist project with GraphQL 😍

## About
> This is extremely simple and fast, I love this technology and I will use it in the future. 🚀🧡

## Querys / Mutation
```js

query {
  users { // fields you want to receive
    name,
    email
  }

  // params to get user by id
  user(id: 1) { 
    name
  }
}

mutation { // fields to send before creating user
  createUser(name: "Alan", email: "alan@gmail.com") {
    id // fields you want to receive after creating the user
  }
}
```
