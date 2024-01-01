---
sidebar_position: 3
---

# PUT

## Update a User by ID

### Endpoint

`PUT /users/:id`

### Description

Updates the details of a specific user by their ID.

### Parameters

- `:id` (integer) - User ID

### Request Body

A JSON object representing the updated user details.

```json
{
  "name": "Updated Name",
  "email": "updated.email@example.com"
}
```

## Example

```bash
curl -X PUT -H "Content-Type: application/json" -d '{"name":"Updated Name","email":"updated.email@example.com"}' http://localhost:3000/users/1
```
