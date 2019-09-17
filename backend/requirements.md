# Backend task

This task is for demonstrating your understanding of HTTP, REST, Node.js and general API practices.

Instructions:

1. Implement API with any node framework and MongoDB.

2. Add following API’s.

3. GET - `host/api/actors` will return

```js
[{
    name
    birthday
    country
 }]
```

4. POST - `host/api/user/signup` will accept `username`, `password` and will return jwt token. `username` must be unique.

```js
{
    token
}
```

5. POST - `host/api/user/login` will accept `username`, `password` and will return jwt token.

```js
{
    token
}
```

6. Authenticated route. GET - `host/api/movies` will return

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
8. End.

