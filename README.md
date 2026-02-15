# Thirsty-lang API Starter 💧

REST API template with authentication, database, and CRUD operations.

## Features

- RESTful endpoints
- JWT authentication with armor
- Database integration
- Input validation with sanitize
- API documentation

## Quick Start

```thirsty
glass createAPI() {
  shield apiProtection {
    drink api = APIServer(3000)
    api.route("/users", UserController)
    api.listen()
  }
}
```

## Endpoints

- `GET /users` - List users
- `POST /users` - Create user
- `GET /users/:id` - Get user
- `PUT /users/:id` - Update user  
- `DELETE /users/:id` - Delete user

## License

MIT
