# Backend task

The following API tasks are for demonstrating your understanding of HTTP, Node.js, and general API practices.

Task 1.  GET - `host/api/actors` will return

```js
[{
    name
    birthday
    country
 }]
```

Task 2. POST - `host/api/user/signup` will accept `username`, `password` and will return jwt token. `username` must be unique.

```js
{
    token
}
```

Task 3. POST - `host/api/user/login` will accept `username`, `password` and will return jwt token.

```js
{
    token
}
```

Task 4. Authenticated route. GET - `host/api/movies` will return

```js
[{
    title
    year
    rating
    actors: [{
      name
      birthday
      country
    }]
  }]
```

Preferred libraries:
  1. Express
  2. Mongoose
