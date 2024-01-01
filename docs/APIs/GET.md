---
sidebar_position: 1
---

# GET

## Retrieve All Users

### Endpoint

`GET /users`

### Description

Retrieves a list of all users.

### Example

```bash
curl http://www.jsonplaceholder.com/users
```

## Retrieve a User by ID

### Endpoint

- GET /users/:id \*

### Description

Retrieves details of a specific user by their ID.

### Parameters

- :id (integer) - User ID

## Example

```bash

curl http://www.jsonplaceholder.com/users/1
```
