# Backend task

The following API tasks are for demonstrating your understanding of HTTP, Node.js, and general API practices.

Task 1.  GET - `host/api/actors` will return

```js
[{
    name: 'name',
    birthday: 'birthday',
    country: 'country'
 }]
```

Task 2. POST - `host/api/user/signup` will accept `username`, `password` and will return jwt token. `username` must be unique.

```js
{
    token: 'token'
}
```

Task 3. POST - `host/api/user/login` will accept `username`, `password` and will return jwt token.

```js
{
    token: 'token'
}
```

Task 4. Authenticated route. GET - `host/api/movies` will return

```js
[{
    title: 'title',
    year: 'year',
    rating: 'rating',
    actors: [{
      name: 'name',
      birthday: 'birthday',
      country: 'country'
    }]
  }]
```

Preferred libraries:
  1. Express
  2. Mongoose
