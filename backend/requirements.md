# Backend task

This task is for demonstrating your understanding of HTTP, Node.js and general API practices.

Preferred libraries:
  1. Express
  2. Mongoose

Instructions:

1. Implement with any node framework and MongoDB.

2. Add following API’s.

*  GET - `host/api/actors` will return

```js
[{
    name
    birthday
    country
 }]
```

* POST - `host/api/user/signup` will accept `username`, `password` and will return jwt token. `username` must be unique.

```js
{
    token
}
```

* POST - `host/api/user/login` will accept `username`, `password` and will return jwt token.

```js
{
    token
}
```

 * Authenticated route. GET - `host/api/movies` will return

```js
[{
    title
    year
    rating
    actors: [{
      name
      birthday
      country
    }]
  }]
```
3. End.

