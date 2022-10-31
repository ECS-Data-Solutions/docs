# Create User

### Request
POST `/`

### Headers
None

### Payload
```json
{
	"name": "Spam",
	"fullname": "Spam Eggs",
	"email": "spam@eggs.com",
	"password": "SpamEggs"
}
```

### Query
None

## Responses
> These are all example responses

### 201
```json
{
    "id": "1",
    "name": "Spam",
    "fullname": "Spam Eggs"
}
```