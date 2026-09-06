# Week 1 - Lab 1
## 1. GET Request
### Command
```bash
curl.exe -i https://api.github.com/users/torvalds

## Status Code

### 200 OK
`200 OK` means the request was successful.

## Response Headers

### 1. Content-Type
`application/json`

This tells us that the response data is in JSON format.

### 2. Cache-Control
`public, max-age=60`

This tells us how the response can be cached.

### 3. ETag
ETag is used to identify a version of the response.

## Response Body
The response body contains the GitHub user information.

Some fields are:
- `login` - GitHub username
- `name` - User's name
- `company` - Company name
- `location` - User's location
- `public_repos` - Number of public repositories
- `followers` - Number of followers

## Observation

The GET request was successful. The server returned `200 OK` and the user information in JSON format.
