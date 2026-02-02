# API Testing

## Tool
Postman

## API Under Test
ReqRes Public API  
Base URL: https://reqres.in/api

## API Scenarios

### Login API
- POST /login
- Positive: valid credentials
- Negative: missing password

### Get Users API
- GET /users?page=2
- Validate status code
- Validate response structure

## Validations
- Status codes
- Response body
- Error messages
