# Login

### Request
POST `/login`

### Headers
None

### Payload
```json
{
	"email": "spam@eggs.com",
	"password": "SpamEggs"
}
```

### Query
None

## Responses
> These are all example responses

### 200
```json
{
	"msg": "Authentication successful",
	"token": "(login token)"
}
```

### 404
```json
{
	"status_code": 404,
	"detail": "User not found"
}
```

### 401
```json
{
	"status_code": 401,
	"detail": "Invalid password"
}
```