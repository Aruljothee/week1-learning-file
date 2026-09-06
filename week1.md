# Week 1 - Lab 1

## 1. GET Request

### Command

```bash
curl.exe -i https://api.github.com/users/torvalds
```

### Status Code

**200 OK** - The request was successful and the requested GitHub user information was returned.

### Three Interesting Response Headers

1. **Content-Type: application/json; charset=utf-8**
   - This tells the client that the response data is in JSON format and uses UTF-8 character encoding.

2. **Cache-Control: public, max-age=60, s-maxage=60**
   - This provides caching instructions. The response can be cached for up to 60 seconds.

3. **ETag**
   - This is an identifier for a specific version of the response. It can be used for cache validation.

### Response Body

The response body contains information about the GitHub user `torvalds` in JSON format.

For example, it contains fields such as:

- `login`
- `name`
- `company`
- `location`
- `public_repos`
- `followers`
