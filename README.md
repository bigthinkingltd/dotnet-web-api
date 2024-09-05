## Big Thinking Ltd.

## BarebonesAPI

The barebones API is a really simple .NET Core based API (with NUnit tests) which server as a staging ground for all
sorts of useful utils. The list below highlights the utils that you will need to build, along with sensible test coverage for this to be useful.

## Utility Endpoints

### /api/health

This isn't a utility it's just a health check, you can just return HTTP 200 to show the endpoint is up.

### /api/{string}/is-palindrome

This utility will take a `string` in the path and return a simple `true` or `false` based on whether the given string is a palindrome.

### /api/{string}/length

This utility will take a `string` in the path and return the length, in terms of number of characters, as an integer.

### /api/{string}/reverse

This utility will take a `string` and reverse it, returning the result as a `string` in kind.