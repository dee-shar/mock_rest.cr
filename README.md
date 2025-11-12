# mock_rest.cr
Web-API for [mockrest.com](https://mockrest.com) the fastest way to mock REST APIs for development and testing.

## Example
```cr
require "./mock_rest"

mock_rest = MockRest.new
users = mock_rest.get_users()
puts users
```
