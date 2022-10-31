# Get a user by an ID

### Request
GET `/`

### Headers
None

### Payload
None

### Query
`?user_id=(user_id)`

## Responses
> These are all example responses

### 200
```json
{
    "id": "1",
    "name": "Spam",
    "fullname": "Spam Eggs"
}
```

### 404
```json
{
	"status_code": 404,
	"detail": "User not found"
}
```