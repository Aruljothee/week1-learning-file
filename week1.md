# Week 1 - Lab 1

## 1. GET Request

### Command

```bash
curl.exe -i https://api.github.com/users/torvalds
```

### Status Code

#### 200 OK

The request was successful and the GitHub user details were received.

### Response Body

- `login` - GitHub username
- `name` - User name
- `company` - Company name
- `location` - User location
- `public_repos` - Number of public repositories
- `followers` - Number of followers

### Observation

I used the GET request to get the GitHub user details. The request was successful and returned `200 OK`. The response data was in JSON format.

## 2. Verbose GET Request

### Command

```bash
curl.exe -v https://httpbin.org/get
```
### Status Code

#### 200 OK

The request was successful and the server returned a response.

### Response Body

The response body contains information about the request, including the request headers, origin, and URL.

### Observation

I used the verbose curl command to view the complete request and response details. It showed the connection, HTTP request, response status, headers, and response body.

## 3. POST Request

### Command

```bash
curl.exe -i -X POST https://httpbin.org/post -H "Content-Type: application/json" -d "{\"name\":\"Arul\",\"week\":1}"
```
### Status Code

200 OK

The request was successful and the server returned a response.

### Response Body

The response body contains information about the request, including the request headers, origin, and URL.

### Observation

I used the verbose curl command to view the complete request and response details. It showed the connection, HTTP request, response status, headers, and response body.

## 4. Query Parameters

### Command

```bash
curl.exe -i "https://httpbin.org/get?role=intern&track=python"
```
### Status Code

200 OK

The request was successful and the server returned a response.

### Observation

I used query parameters in the URL to send additional information to the server. The response showed the values of role and track in JSON format.
