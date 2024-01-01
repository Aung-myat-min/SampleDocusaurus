---
sidebar_position: 2
---

# POST

## Create a New User

### Endpoint

`POST /users`

### Description

Creates a new user and returns the user details.

### Request Body

A JSON object representing the new user.

```json
{
  "name": "John Doe",
  "email": "john.doe@example.com"
}
```

## Example

```bash
curl -X POST -H "Content-Type: application/json" -d '{"name":"John Doe","email":"john.doe@example.com"}' http://localhost:3000/users
```
