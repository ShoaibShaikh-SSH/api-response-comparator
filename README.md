# A comparator library that can be used to compare 2 API responses (HTTP/HTTPS)

Two files with multiple request URLs will be input to the code.

Sample content for files:
Each file contains (HTTP/HTTPS) API's separated by a new line.

| File1    | File2 |
| -------- | ------- |
| https://reqres.in/api/users/3  | https://reqres.in/api/users/2    |
| https://reqres.in/api/users/1 | https://reqres.in/api/users?page=3     |
| https://reqres.in/api/users/2    | /api/unknown/2    |
| https://reqres.in/api/users?page=2    | https://reqres.in/api/users?page=2    |
