# Week 1 - Lab 1

## 1. GET Request

### Command

```bash
curl.exe -i https://api.github.com/users/torvalds
Status Code
200 OK

The request was successful and the GitHub user details were received.

Response Headers
1. Content-Type

application/json

This means the response is in JSON format.

2. Cache-Control

public, max-age=60

This tells us how the response can be cached.

3. ETag

ETag is used to identify the version of the response.

Response Body

The response body contains the details of the GitHub user torvalds.

Some of the fields I observed are:

login - GitHub username
name - User name
company - Company name
location - User location
public_repos - Number of public repositories
followers - Number of followers
